<script>
    let props = $props();
</script>

<div class="radial-progress text-primary"
     style={`--value:${props.value}; --size:20rem; --thickness: 2rem;`}
     aria-valuenow="20"
     role="progressbar"
>
    <div class="text-center text-base-content text-3xl">
        <p class="text-accent text-4xl">{props.value}%</p>
        <p>Completed</p>
    </div>
</div>