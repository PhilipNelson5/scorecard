<div class="flex">
    <GameCard title_text="Lost Ruins of Arnak" image_url="games/lost_ruins_of_arnak.jpg"/>
    <GameCard title_text="Wingspan" image_url="games/wingspan.jpg"/>
    <GameCard title_text="7 Wonders" image_url="games/7_wonders.jpg"/>
    <GameCard title_text="Scythe" image_url="games/scythe.jpg"/>

    <GameCard title_text="Lost Ruins of Arnak" image_url="games/lost_ruins_of_arnak.jpg"/>
    <GameCard title_text="Wingspan" image_url="games/wingspan.jpg"/>
    <GameCard title_text="7 Wonders" image_url="games/7_wonders.jpg"/>
    <GameCard title_text="Scythe" image_url="games/scythe.jpg"/>
    <GameCard title_text="Lost Ruins of Arnak" image_url="games/lost_ruins_of_arnak.jpg"/>
    <GameCard title_text="Wingspan" image_url="games/wingspan.jpg"/>
    <GameCard title_text="7 Wonders" image_url="games/7_wonders.jpg"/>
    <GameCard title_text="Scythe" image_url="games/scythe.jpg"/>
    <GameCard title_text="Wingspan" image_url="games/wingspan.jpg"/>
    <GameCard title_text="7 Wonders" image_url="games/7_wonders.jpg"/>
    <GameCard title_text="Scythe" image_url="games/scythe.jpg"/>
    <GameCard title_text="Lost Ruins of Arnak" image_url="games/lost_ruins_of_arnak.jpg"/>
</div>

<script lang="ts">
    import GameCard from "@components/GameCard.svelte";
</script>

<style lang=scss>
.flex {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
      
    &:after {
        content: "";
        flex: auto;
    }
}
</style>