<script>
    let num = 0;
    function plus() {
        num += 1;
    }
    function minus() {
        num -= 1;
    }
    function reset_zero() {
        num = 0;
    }
</script>
<h1>this is Counter Page</h1>
<div>now num is {num}</div>
<button on:click={plus}>+</button>
<button on:click={minus}>-</button>
<button on:click={reset_zero}>reset</button>