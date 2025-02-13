<html lang="es">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1>¡Ta daaaa! 🎉</h1>
    <p>Contribuyendo mi creatividad, ¡¡Feliz día!!</p>
    <img src="https://img.freepik.com/fotos-premium/perro-ramo-flores-boca_12395-1671.jpg" alt="Imagen Especial">
    <audio id="audio" loop>
        <source src="data:audio/mpeg;base64,SUQzBAAAAAAAf1RYWFgAAAASAAADbWFqb3JfYnJhbmQAZGFzaABUWFhYAAAAEQAAA21pbm9yX3ZlcnNpb24AMABUWFhYAAAAHAAA..." type="audio/mpeg">
    </body>
    <audio controls autoplay loop>
        <source src="https://drive.google.com/uc?export=download&id=1G-SQEG4xgkwwdrguGm_3hYiEQHPmSRur" type="audio/mpeg">
        Tu navegador no soporta el elemento de audio.
    </audio>
    <button onclick="playAudio()" style="padding: 10px; font-size: 16px;">Reproducir música 🎵</button>
    <script>
        function playAudio() {
            var audio = document.getElementById('audio');
            audio.play();
        }
</html>
