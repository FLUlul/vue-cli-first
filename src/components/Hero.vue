<template>
  <div>
        <div class="jumbo">

            <div>

                <h2>Forza Horizon 5</h2>

                <p>Nuovo gioco di guida in GamePass</p>

            </div>

        </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo {
  width: 100vw;
  height: 500px;
  background-image: url("https://www.tomshw.it/images/images/2021/10/forza-horizon-5-190529.jpg");
  background-position: center;
  position: relative;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.jumbo div{
    position: absolute;
    bottom: 10px;
    left: 10px;
    color: black;
    text-shadow: 1px 1px 10px white;
}
.jumbo div h2{
    text-align: start;
    font-size: 50px;
}
.jumbo div p{
    font-size: 30px;
}
</style>