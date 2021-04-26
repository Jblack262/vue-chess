<template>
  <div class="board">
    <div class="row">
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
    <div class="row e">
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
    <div class="row">
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
    <div class="row e">
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
    <div class="row">
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
    <div class="row e">
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
    <div class="row">
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
    <div class="row e">
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
    <div class="row">
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
    <div class="row e">
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
    <div class="row">
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
    <div class="row e">
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
