Week9_Lab
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
	<h1>Form</h1>
	<p>Please fill out this form about what music you like.</p>

	<form method="post" action="">
		<p>Name:
		<input type="text" name = "name" value = ""></p>
		<p>Email Address:
		<input type="text" name = "name" value = ""></p>
		<h4>Genres you like:</h4>
		<input type="checkbox" name="Genre" value="Rock">Rock
		<input type="checkbox" name="Genre" value="Jazz">Jazz
		<input type="checkbox" name="Genre" value="Metal">Metal
		<input type="checkbox" name="Genre" value="Punk">Punk
		<input type="checkbox" name="Genre" value="Country">Country
		<input type="checkbox" name="Genre" value="Pop">Pop
		<input type="checkbox" name="Genre" value="Hiphop">Hiphop
		<h4>How did you learn about this form?</h4>
		<input type="radio" name="how" value="Facebook">Facebook
		<input type="radio" name="how" value="Instagram">Instagram
		<input type="radio" name="how" value="Line">Line
		<input type="radio" name="how" value="Friends">Friends
		<input type="radio" name="how" value="Other">Other
		<h4>Please rate us!</h4>
		<select name= "Rate">
		<option value="Not Bad">Not Bad</option>
		<option value="Good">Good</option>
		<option value="Couldn't Be Better">Couldn't Be Better</option>
		<option value="Not My Type">Not My Type</option>
		</select>
		<input type="Submit">
	</form>
</body>
</html>
