<template>
    <div :id="'pawn' + id" class="pawn" :class="[(selected == id) ? 'selected' : '']" @click="clicked" :style="{left: `${posX * tileWidth}px`, top: `${posY * tileWidth}px`, width: `${tileWidth}px`, height: `${tileWidth}px`}">
        <i class="fas fa-chess-pawn"></i>
    </div>

</template>
<script>
export default {
  name: 'pon',
  data: () => ({
      
  }),
  props: {
      id: Number,
      posX: Number,
      posY: Number,
      tileWidth: Number,
      selected: Number,
  },
  methods: {
      clicked() {
          this.$emit('pawnClick', this.id);
      }
  }
}
</script>

<style scoped lang="scss">
.pawn {
    box-sizing: border-box;
    display: grid;
    place-items: center;
    position: absolute;
    font-size: 250%;
    color: black;
    text-shadow:
        -1px -1px 0 #fff,  
        1px -1px 0 #fff,
        -1px 1px 0 #fff,
        1px 1px 0 #fff;
    &.selected {
        border: 2px solid lime;
    }
}
</style>