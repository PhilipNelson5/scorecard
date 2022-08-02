<div class="container">
    <div class="card">
        <img src={image_url} alt={title_text}>
    </div>
    <p class="title">{title_text}</p>
</div>

<script lang="ts">
export let image_url: string;
export let title_text: string;
</script>

<style lang="css">
.container {
    width: 7em;
    height: 8em;
}

.card {
    overflow: hidden;
    border-radius: .5em;
    margin: auto;
    margin-bottom: 5px;
    width: 6em;
    height: 6em;
    box-shadow: rgba(0, 0, 0, 0.35) 4px 4px 2.5px;
}

.title {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    text-align: center;

    font-family: Roboto;
    font-weight: 400;
    font-size: 10px;
    margin: 0;
}

.card:hover {
    transform: translateY(1px);
    transition-duration: 100ms;
    box-shadow: rgba(0, 0, 0, 0.45) 3px 3px 2px;
}

img {
    width: 6em;
    height: 6em; 
    object-fit: cover
}
</style>