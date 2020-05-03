<template>
  <div class="page-index">
    <div class="container">
        <div class="row">
            <div class="col-sm-12"> <h2>Acerca de mi</h2><span class="emoji-title emoji--writing"/> <hr> </div>
            
        </div>
      
    </div>
  </div>
</template>
<style lang="scss">
.blogs {
  margin: 0;
  
  @media (min-width: $screen-sm){
    grid-template-columns: 1fr 1fr;
    grid-gap: 50px;
    display: grid;
  }

  &__top {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 4rem;
  }
}
</style>