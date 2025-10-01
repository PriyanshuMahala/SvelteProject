<script lang="ts">
    let count = $state(0);

    function increment(){
        count++;
    }
</script>

<h1>{count}</h1>


<button class="text-blue-600 hover:text-blue-200 active:text-red-400 transition-all duration-200"
onclick={increment} >Click here</button>