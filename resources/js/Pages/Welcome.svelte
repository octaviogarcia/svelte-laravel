<script>
    let contador = 0;
    const click = () => contador++;
    const saludo = 'Hola Mundo!';
</script>

<h1>{saludo}</h1>
<button on:click={click}>PROGRAMEE {contador}</button>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
