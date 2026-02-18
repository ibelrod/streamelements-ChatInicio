# streamelements-ChatInicio<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Alertas</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div id="alert">
  <span id="username"></span>
  <span id="message"></span>
</div>

<script src="alerts.js"></script>
</body>
</html>
body {
  margin: 0;
  background: transparent;
  font-family: Arial, sans-serif;
}

#alert {
  font-size: 48px;
  color: #00ff88;
  animation: pop 0.5s ease;
}

@keyframes pop {
  from { transform: scale(0); opacity: 0; }
  to   { transform: scale(1); opacity: 1; }
}
body {
  margin: 0;
  background: transparent;
  font-family: Arial, sans-serif;
}

#alert {
  font-size: 48px;
  color: #00ff88;
  animation: pop 0.5s ease;
}

@keyframes pop {
  from { transform: scale(0); opacity: 0; }
  to   { transform: scale(1); opacity: 1; }
}
