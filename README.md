# Exercício Inofensiva Flor (Lógica de Programação)

Temos o seguinte esboço de código que declara a função desenhaCirculo. Essa função permite desenhar na tela um círculo no eixo X e Y, inclusive permite ainda definir a sua cor:

```
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
```
A função desenhaCirculo ainda não é usada. *Faça uso da função para desenhar uma flor conforme a imagem abaixo:

![image](https://github.com/paulateshima/exercicio.inofensiva.flor/assets/170154538/861fc2ea-72ad-47c5-b148-71442479979a)

Utilize como ponto de referência para o centro da flor (círculo vermelho) as coordenadas 300 (x) e 200 (y).

O código da flor é?
