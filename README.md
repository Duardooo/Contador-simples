# Contador-simples 

Primeiro trabalho 
nova alteração1
nova alteração local certo ??
altera algo
ultima alteração
altera ultima
<!DOCTYPE html>
<html>

<body>
    <script>
        var contador = 0;
        function aumentaContador() {
            contador++;
            let label = document.querySelector("label")
            label.innerText = `Contador: ${contador}`;
        }
    </script>
    <button onclick="aumentaContador()">
        Clique aqui
    </button>
    <label>
        Contador: 0
    </label>
</body>

</html>