<template>
    <div class="jumbotron">
        <h2>
            Questa è una prova di jumbotron, direi che per essere la prima va bene... Metto Slam Dunk perchè mi piace.
        </h2>
        <div class="container-image">
            <img src="https://www.staynerd.com/wp-content/uploads/slam-dunk.jpg" alt="slamDunk">
        </div>
    </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron {
    display: flex;
    width: 80%;
    height: 500px;
    margin: auto;
    background-color: #42b983;
}
h2 {
    font-size: 40px;
    color: white;
}
.container-image {
    height: 100%;
}
img {
    height: 100%;
    object-fit: contain;
}
</style>