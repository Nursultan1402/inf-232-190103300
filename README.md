FROM vapor/vapor:1.0.9-xenial

FROM swift:4.1
WORKDIR /app

COPY ./ ./

RUN vapor build

ADD . ./
RUN git submodule update --init --recursive
RUN swift package clean
RUN swift build -c release
RUN mkdir /app/bin
RUN mv `swift build -c release --show-bin-path` /app/bin
EXPOSE 8080

# CMD vapor run

ENTRYPOINT ./bin/release/Run serve -e prod -b 0.0.0.0
