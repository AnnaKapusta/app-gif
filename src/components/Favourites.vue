<template>
    <div class="container">
        <h3>Your favourites GIFs :</h3>
        <div class="row col results-content mx-auto">
            <FavouritesItem />
        </div>

    </div>
</template>

<script>
    import FavouritesItem from './FavouritesItem'

    export default {
        name: 'Favourites',
        components: { FavouritesItem },
    }
</script>

<style scoped>
    .results-content {
        border: 2px solid #252525;
        min-height: 300px;
    }

</style>
