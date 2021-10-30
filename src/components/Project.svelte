<script lang="ts">
    export let id: number;
    export let name: string;
    export let description: string;
    export let from: string;
    export let to: string;
    export let imageUrl: string;
</script>

<div id="{id}" class="project" style="background-image: url({imageUrl})">
    <h3>{name}</h3>
    {from} ~ {to}<br/>
    <small>{description}</small><br/>
</div>

<style lang="css">
.project {
    width: 300px;
    height: 600px;
    background-repeat: no-repeat;
    background-size: 100% auto;
    background-blend-mode: soft-light;
}
</style>