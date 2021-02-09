<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>First Task</title>

</head>
<body>
	<div class="block1">
		<div>Home Page</div>
		<div>Stuff</div>
        <div>Curriculum</div>
        <div>Course Schedule</div>
		<div>About us</div>
	</div>
	<div class="block2">
		<div class="photo">
			<img src="1.jpg" alt="photo" style="width: 350px; height: 250px;"
		</div>


		<div class="info">
			<h1>Student Information</h1>
			<table border="1">
				<tr>
					<td>Name</td>
					<td>Meruyert</td>
				</tr>
				<tr>
					<td>Surname</td>
					<td>Khuankyzy</td>
				</tr>
				<tr>
					<td>ID</td>
					<td>190103242</td>
				</tr>
				<tr>
					<td>Email:</td>
					<td>190103242@stu.sdu.edu.kz</td>
				</tr>
				<tr>
					<td>City</td>
					<td>Kaskelen</td>
				</tr>
				<tr>
					<td>Advistor</td>
					<td>Marzhan Bekbalanova</td>
				</tr>
				<tr>
					<td>Grant type</td>
					<td>State grant</td>
				</tr>
			</table>



		</div>
	</div>
	<hr>
	<div class="block3">
		<div><h3>Do you have any problem?</h3></div>
	</div>
	<div class="block4">
		<textarea name="" id="" cols="150" rows="10"></textarea>
	</div>

	<style >
		.block1{
    display:flex;
    justify-content: center;
    background-color: dodgerblue;
    height: 60px;



}
.block1 > div{
    margin: 20px 70px;
    color: floralwhite;

}

.block2 .photo {
    display: inline;   
}
.block2 .photo img{
    margin: 55px 120px;

}
.block2 .info {
    display: inline-block;
    width: 350px;
    margin: 0px 30px;
    padding: 30px;
    text-align: right;
    vertical-align: top;
}
.block3 {
    text-align: center;
    margin: 4px;
}
.block4 {


  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 140px;


}
th, td {
    padding: 1px 55px 1px 55px;
    text-align: center;

  }

	</style>

</body>
</html> 
