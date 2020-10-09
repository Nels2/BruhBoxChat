<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>BruhBox Server</title>
	<link href="css/style.css" rel="stylesheet" type="text/css" />
	<link rel="shortcut icon" type="image/x-icon" href="images/fav.png">
</head>

<body>
	<div class="app">
		<div class="list">
			<span id="typed"></span>
		</div>
		<div class="interface">
			<input type="text" id="message" autofocus>
		</div>
	</div>
	<div id="typed-strings">
		<p>Welcome the to BruhBox Server platform.<br> ^500 To join a room or create a new one, just add "/[room]/[username]" to the end of the current
			url!<br> ^500 You
			can also share a room by copying the url while in a room (minus the "/[user]" part)<br><br> ^500 You can also just
			type in a room name and hit enter to create/join a room.<br> made by icx</p>
	</div>
	<script src="/socket.io/socket.io.js"></script>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.9"></script>
	<script src="js/room.js"></script>
</body>

</html>
