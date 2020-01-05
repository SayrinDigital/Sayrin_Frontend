<template lang="pug">
 
  div
    .uk-container.uk-container-expand-right
      div(class="uk-flex uk-flex-middle", uk-grid)
        div(class="uk-width-2-5@m")
          h1.uk-heading-large(class="uk-width-xlarge@l") Te ayudamos a construir tu producto.
          p(class="uk-width-xlarge@l")  Whether you're going on a business trip or relocating to a new city.
          .uk-margin  
            a Get Started
            a.uk-margin-small-left View Our Clients
        div(clasS="uk-width-3-5@m")
          div.uk-container-item-padding-remove-right
            div
              img.uk-width-1-2(src="https://images.unsplash.com/photo-1552960562-daf630e9278b?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80", alt="alt")
              img.uk-width-1-2(src="https://images.unsplash.com/photo-1552960562-daf630e9278b?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80", alt="alt")

        form(name="contact", method="POST", data-netlify="true")
          input(type="text" name="name", placeholder="Nombre")
          input(type="email" name="email", placeholder="Email")
          button(type="submit") Send
    


</template>

<script>


export default {
  components: {
    
  }
}
</script>

<style lang="scss" scoped>

  .text-home-container{
    position: relative;
    z-index: 1;
  }

  .home-image{
    position: absolute;
    right: 0;
    top: 0;
    z-index: 0;
  }

</style>