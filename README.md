# Registration-form<!DOCTYPE html>
<html>
<body>
<head>
    <meta name="viewport" content="width=device-width, initiaL
    -scale=1.0">
    </head>
<h1 style="text-align:center;">TCS Exam Registration Form</h1>
<form>
    <style>
body, html {
  height: 100%;
  font-family: Arial, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

.bg-img {
  background-image: url("img_nature.jpg");

  min-height: 380px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
.container {
  position: absolute;
  right: 0;
  margin: 20px;
  max-width: 300px;
  padding: 16px;
  background-color: white;
}
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
.btn {
  background-color: #04AA6D;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.btn:hover {
  opacity: 1;
}
</style>
</head>
<body>
</div>
  <label for="name">Student Name:</label><br>
  <input type="text" id="name" name="name" value=""><br>
  <label for="rnum">Roll number:</label><br>
  <input type="text" id="rnum" name="rnum" value=""><br>
  <label for="faname">Father name:</label><br>
  <input type="text" id="faname" name="faname" value=""><br>
  <label for="moname">Mother name:</label><br>
  <input type="text" id="moname" name="moname" value=""><br>
  <label for="faocu">Father Occupation:</label><br>
  <input type="text" id="faocu" name="faocu" value=""><br>
  <label for="mocu">Mother Occupation:</label><br>
  <input type="text" id="mocu" name="mocu" value=""><br>
  <label for="adnum">Student Aadhar no:</label><br>
  <input type="text" id="adnum" name="adnum" value=""><br>
  <label for="add">Permanent Address:</label><br>
  <input type="text" id="add" name="add" value=""><br>
    <label for="mail">Email Id:</label><br>
  <input type="text" id="mail" name="mail" value=""><br>
  <label for="edqua">Education Qualification:</label><br>
  <input type="text" id="edqua" name="edqua" value=""><br>
  <label for="xgpa">Xth CGPA:</label><br>
  <input type="text" id="xgpa" name="xgpa" value=""><br>
  <label for="xiigpa">XII CGPA:</label><br>
  <input type="text" id="xiigpa" name="xiigpa" value=""><br>
  <label for="cocmpltd"><u>Courses Completed</u>:</label><br>
  <input type="checkbox" id="course1" name="course1" value="">
  <label for="course1">C</label><br>
  <input type="checkbox" id="course2" name="course2" value="">
  <label for="course2">Java</label><br>
  <input type="checkbox" id="course3" name="course3" value="">
  <label for="course3">Python</label><br>
  <input type="checkbox" id="course4" name="course4" value="">
  <label for="course4">C++</label><br>
  <input type="checkbox" id="course5" name="course5" value="">
  <label for="course5">HTML</label><br>
  <input type="checkbox" id="course6" name="course6" value="">
  <label for="course6">CSS</label><br>
  <input type="checkbox" id="course7" name="course7" value="">
  <label for="course7">JavaScript</label><br>
  <label for="cocmpltd"><u>Gender</u></u>:</label><br>
  <input type="radio" id="m" name="gender" value="male">
<label for="female">Male</label><br>
<input type="radio" id="f" name="gender" value="female">
<label for="female">Female</label><br>
<input type="radio" id="o" name="gender" value="others">
<label for="others">Others</label><br>
<form action="upload.php" method="post" enctype="multipart/form-data">
  <u>Upload your Image</u>:<br>
  <br>
  <input type="file" name="fileToUpload" id="fileToUpload">
  <input type="submit" value="Upload Image" name="submit"><br>
  <u>Upload your Resume</u>:<br>
  <br>
  <input type="file" name="fileToUpload" id="fileToUpload">
  <input type="submit" value="Upload Resume" name="submit"><br>
  <br>
  <button type="register" class="registerbtn">Register</button>
</form>
</body>
</html>
