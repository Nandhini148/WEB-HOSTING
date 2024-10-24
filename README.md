<!DOCTYPE html>
<html>
<head>
	<title>Student Registration Form</title>
</head>
<body>

	<h1>Student Registration Form</h1>
<!-- Search bar -->
	<div>
		<input type="text" placeholder="Search...">
		<button type="button">Search</button>
	</div>
<form action="submit-form.php" method="POST" enctype="multipart/form-data">
    <!-- form fields here -->
</form>
	<form>
		<label for="username">Username:</label>
		<input type="text" id="username" name="username"><br><br>
		
		<label for="password">Password (16 characters, 1 uppercase, 1 lowercase, 1 number, 1 special character):</label>
		<input type="password" id="password" name="password" pattern="^(?=.[a-z])(?=.[A-Z])(?=.\d)(?=.[@$!%?&])[A-Za-z\d@$!%?&]{16}$"><br><br>
		
		<label for="mailid">Mail ID:</label>
		<input type="email" id="mailid" name="mailid"><br><br>
		
		<label for="department">College Department:</label>
		<input type="text" id="department" name="department"><br><br>
		
		<label for="rollnumber">Roll Number:</label>
		<input type="number alphabet" id="rollnumber" name="rollnumber"><br><br>
		
		<label for="image">Image Upload (JPG):</label>
		<input type="file" id="image" name="image" accept="image/jpeg"><br><br>
		
		<input type="submit" value="Register">
	</form>
</body>
</html>
