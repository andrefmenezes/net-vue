<template>
  <div ref="scroller" class="row">
        <div class="row__inner">
          <div class="gui-card">
            <div class="gui-card__media">
              <img class="gui-card__img" :src="imagem" alt=""  />
            </div>
            <div class="gui-card__details">
              <div class="gui-card__title">
                {{titulo}}
              </div>
            </div>
          </div>
          </div>
          </div>

</template>

<script>
export default{  
  props:['titulo','imagem']
}

</script>

<style lang="scss">


</style>
