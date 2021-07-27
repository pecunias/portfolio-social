<template>
    <ui-card v-ripple>
    <ui-card-content v-ripple>
        <div>
        <ui-card-media
            
        >test</ui-card-media>
        <div>
            <div :class="[$tt('headline5')]">Rozes</div>
        </div>
        </div>
    </ui-card-content>
    
    </ui-card>
</template>

<script>
export default {
  name: 'StockCard',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.yellow {
  background: yellow;
}

.demo {
  border: 1px solid;
}

.demo .mdc-layout-grid__inner {
  background: cyan;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
