<script lang="ts">
    let text = $state(" ");

</script>


<div class="flex justify-center"> 
    <input type="text" bind:value={text} placeholder="Enter text" required >
</div>
<div class="flex h-screen justify-center ">
    <p >{text}</p>
</div>