<template>
  <div id="app">
    <div class="chess">
      <Board :tileWidth="50"/>
      <Pawn v-for="pawn in pawns" :key="pawns[pawn]" :id="pawns[pawn]" :selected="selected" @pawnClick="selectPawn" :tileWidth="50" :posX="pawnPos[pawn][0]" :posY="pawnPos[pawn][1]"/>
    </div>

  </div>
</template>

<script>
import Board from './components/board.vue'
import Pawn from './components/pon.vue'

export default {
  name: 'App',
  data() {
    return {
      pawns: [0,1,2,3,4,5,6,7,8,9,10,11],
      pawnPos: [[0,1],[1,1],[2,1],[3,1],[4,1],[5,1],[6,1],[7,1],[8,1],[9,1],[10,1],[11,1]],
      selected: undefined,
    }
  },
  components: {
    Board,
    Pawn,
  },
  methods: {
    selectPawn(id) {
      this.selected= id;
      console.log(this.selected)
    }
  }
}
</script>

<style lang="scss">
html, body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  .chess {
    display: flex;
  }
}
</style>
