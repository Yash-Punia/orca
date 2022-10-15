<script>
	import { state } from "$lib/stores/global";

    let buttons = [];
        
    const changeState = (element, /** @type {string} */ newState) => {
        if($state != newState)
        {
            state.set(newState);
            buttons.forEach(button => {
                button.classList.remove("selected")
            })
            element.classList.toggle("selected")
        }
        
    }

</script>

<div class="flex flex-col border-r-2 border-black min-h-screen">
    <h1 bind:this={buttons[0]} on:click={e => changeState(e.target, "buttons")} class="hover:bg-gray-200 transition-all cursor-pointer border-b-2 border-black text-center px-4 py-2 selected">Buttons</h1>
    <h1 bind:this={buttons[1]} on:click={e => changeState(e.target, "navbars")} class="hover:bg-gray-200 transition-all cursor-pointer border-b-2 border-black text-center px-4 py-2">Navbar</h1>
</div>

<style>
    .selected {
        background-color: black;
        color: white;
    }
</style>