<script lang="ts">
    let text = $state(" ");

</script>


<input type="text" bind:value={text} placeholder="Enter text">
<div class="flex h-screen justify-center ">

    <h1 >{text}</h1>
</div>