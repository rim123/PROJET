PROJET
======<html>
	<head>
		<title>Un formulaire avec HTML5	</title>
		<meta charset="utf-8" />
		<script type="text/javascript" language="javascript" src="jquery.js"></script>
		<script type="text/javascript" language="javascript" src="script.js"></script>
		<link type="text/css" rel="stylesheet" href="style.css" />
	</head>
	<body>
		<div id="div">
			Cliquer içi pour afficher le formulaire
		</div>
		<div id="form">
			<form class="form"  action="form.html" >
				<table>
					<tr>
						<td>Nom:</td><td><input type="text" name="nom" autocomplete="on" autofocus placeholder="Veuillez saisir votre nom" /></td>
					</tr>
					<tr>
						<td>Age:</td><td><input type="number" min="18" max="90" name="age"  /></td>
					</tr>
					<tr>
						<td>Date de naissance:</td><td><input type="date" name="naissance"  /></td>
					</tr>
						</tr>
				</table>
			</form>
		</div>
	</body>
</html>
