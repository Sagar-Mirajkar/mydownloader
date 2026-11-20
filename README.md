<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>MyDownloader</title>
<style>
body{
font-family:sans-serif;
background:#0f172a;
color:white;
padding:20px;
}
input{
width:100%;
padding:12px;
border-radius:10px;
border:none;
margin-bottom:10px;
}
button{
width:100%;
padding:12px;
background:#2563eb;
color:white;
border:none;
border-radius:10px;
}
.card{
background:#1e293b;
padding:20px;
border-radius:15px;
}
</style>
</head>
<body>

<h1>MyDownloader</h1>

<div class="card">
<input id="url" placeholder="Paste URL here">
<button onclick="go()">Open URL</button>
</div>

<script>
function go(){
const url=document.getElementById('url').value;
if(url){
window.open(url,'_blank');
}
}
</script>

</body>
</html>
