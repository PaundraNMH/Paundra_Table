<!DOCTYPE HTML>
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<head>
<title>Form</title>
</head>
<body>
<form action="latihanform.html" method="post" name="registrasi" target="_blank">
<fieldset>
<legend align="center" colspan="3" >Form Registrasi</legend>
FIRST NAME : <input type="text" name="username" placeholder="username"><br><br>
PASSWORD :  <input type="password" name="password" placeholder="password"><br><br>
<label>GENDER : </label>
<input type="radio" name="gender" value="Laki - Laki"><label for="laki">MALE</label>
<input type="radio" name="gender" value="Perempuan"><label for="Perempuan">FEMALE</label><br><br>
ADDRESS : <textarea placeholder="Alamat"></textarea><br><br>
D.O.B
<label for="birthday">Birthday:</label>
<input type="date" id="birthday" name="birthday"><br><br>
<label>SELECT GAMES : </label>
<input type="checkbox" id="hockey"><label for="hockey">Hockey</label>
<input type="checkbox" id="football"><label for="football">Football</label>
<input type="checkbox" id="cricket"><label for="cricket">Cricket</label>
<input type="checkbox" id="volleyball"><label for="volleyball">VolleyBall</label>
<br><br>
<input type="submit" name="kirim" value="Kirim">
<input type="reset" name="rest" value="Reset">
<br>
<br>
<input type="checkbox" id="accept"><label for="accept">I accept this agrement</label>
</fieldset>
</form>
</body>
</html>
