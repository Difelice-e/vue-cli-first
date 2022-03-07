<template>
    <div class="jumbotron">
        <img src="../assets/logo.png" alt="logo-vue">
        <div class="jumbo-text">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto, esse? Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate iusto, doloremque non laudantium delectus pariatur quia sequi deleniti vero excepturi.</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'myFirstJumbo',
}
</script>

<style scoped lang="scss">
.jumbotron {
    background-color: black;
    position: relative;
    width: 100%;
}

.jumbotron img {
    width: 50%;
}

.jumbo-text {
    color: white;
    position: absolute;
    bottom: 0;
    right: 0;
    width: 40%;
}
</style>