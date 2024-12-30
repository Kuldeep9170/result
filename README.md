 <!DOCTYPE html>
<html>
<head>
<title>Embedded Content</title>
</head>
<body>
<iframe src="https://script.google.com/macros/s/AKfycbwV-eQRfuUrZMYDZSAMSolkXyKqbCfOi01iTP_7cR2UbfDiEMlVQk6z1UmOtBJlZtPc/exec"
width="100%"
height="100%"
allowfullscreen="true"
style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; border: none;"></iframe>
<script>
window.onload = function() {
document.querySelector('iframe').requestFullscreen().catch((err) => {
console.error(`Error attempting to enable full-screen mode: ${err.message}`);
});
};
</script>
</body>
</html>
