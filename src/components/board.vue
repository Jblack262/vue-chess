<template>
  <div class="board">
    <div class="row" @click="selectTile(0)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(1)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row" @click="selectTile(2)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(3)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row" @click="selectTile(4)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(5)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row" @click="selectTile(6)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(7)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row" @click="selectTile(8)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(9)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row" @click="selectTile(10)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
    <div class="row e" @click="selectTile(11)">
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
      <div class="square" :style="{width: `${tileWidth}px`, height: `${tileWidth}px`}"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'board',
  props: {
    tileWidth: Number,
  },
  methods: {
    selectTile(y) {
      let mouseX = event.clientX;
      let x = Math.floor(mouseX / this.tileWidth)
      console.log(x)
      this.$emit('tileSelect',x,y)
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$black: rgb(65, 1, 1);
$white: tan;
.board {
  position: absolute;
  margin: 0 auto;
  background: black;
}
  .row {
    display: flex;
    .square {
      width: 50px;
      height: 50px;
      background: $white;
      &:nth-child(odd) {
        background: $black;
      }
    }
    &.e {
      .square:nth-child(even) {
        background: $black;
      }
      .square:nth-child(odd) {
        background: $white;
      }
    }
  }
</style>
