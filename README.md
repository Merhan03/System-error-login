# <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ERROR SYSTEM!</title>
<style>
body { background: black; color: red; font-family: monospace; text-align: center; padding-top: 100px; }
#modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.9); color: red; font-size: 20px; justify-content: center; align-items: center; }
button { margin-top: 20px; padding: 10px 20px; font-size: 18px; }
</style>
</head>
<body>
<h1>ERROR SYSTEM!</h1>
<p>WARNING! Your system has been hacked!</p>

<div id="modal">
  <div>
    <p>ALERT! SYSTEM BREACH DETECTED!</p>
    <p>Your files and personal data are at risk.</p>
    <p>Unauthorized access has been identified.</p>
    <p>All network activity is being monitored.</p>
    <button onclick="closeModal()">Close</button>
  </div>
</div>

<script>
function showModal() {
  document.getElementById('modal').style.display = 'flex';
}

// Modal muncul selepas 2 saat
setTimeout(showModal, 2000);

function closeModal() {
  document.getElementById('modal').style.display = 'none';
}
</script>
</body>
</html>
