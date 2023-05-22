<template>
<div>
    <header class="header">
        <img v-bind:src="'/assets/logo.png'"/>
        <nav-buttons>
            <scale-button class="nav-button">Über mich</scale-button>
            <scale-button class="nav-button">Meine Aquarien</scale-button>
            <scale-button class="nav-button">Impressum</scale-button>
        </nav-buttons>
    </header>
</div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.header{
    position: absolute;
    right: 70px;
    left: 40px;
    top: 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav-button{
    color: white;
    font-size: 30px;
    margin-left: 40px;
}

</style>