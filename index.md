<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
    <script>
        document.addEventListener("DOMContentLoaded", function () {
            var userLang = navigator.language || navigator.userLanguage;
            if (userLang.startsWith("es")) {
                window.location.href = "/index_ES.html"; // Redirect to Spanish version
            } else {
                window.location.href = "/index_EN.html"; // Redirect to English version
            }
        });
    </script>
</head>
<body>
    <p>Redirecting... If you are not redirected, choose: 
        <a href="/index_EN.html">English</a> | <a href="/index_ES.html">Español</a>.
    </p>
</body>
</html>
