# flor_em_js
Uma flor em Javascript

<canvas width="600" height="400"></canvas>

<script>

    var tela = document.querySelector('canvas');
    var pincel = tela.getContext('2d');
    pincel.fillStyle = 'lightgray';
    pincel.fillRect(0, 0, 600, 400);

    function desenhaCirculo(x, y, raio, cor) {

        pincel.fillStyle = cor;
        pincel.beginPath();
        pincel.arc(x, y, raio, 0, 2*3.14);
        pincel.fill();
    }
</script>
