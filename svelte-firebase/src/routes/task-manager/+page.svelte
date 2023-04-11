 <script>
    let count = 0;

    $:{
        console.log(count)
    }
 </script>

 <div class="text-white">
    <h1>{count}</h1>
    <button on:click={() => {
        count++
    }}>add 1</button>
 </div>