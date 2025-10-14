<script>
    import { goto } from "$app/navigation";

    function gioca(){
        goto("/game");
    }
    
</script>
<div>
    <button onclick={gioca}>
        gioca
    </button>
    <button>
        settings
    </button>
</div>