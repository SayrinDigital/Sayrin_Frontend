<template lang="pug">

    nav.uk-navbar-container.uk-navbar-transparent(uk-navbar)
        .uk-navbar-left
            .uk-navbar-item
                nuxt-link(to="/") Say!
        .uk-navbar-right
            ul.uk-navbar-nav
                li
                    nuxt-link(to="/clients") Clientes
                li 
                    a Blog
                li
                    a About Us
            .uk-navbar-item
                a.contact-us-button Contact Us
    
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    nav{
        ul{
            li{
                a{
                    font-family: $title-font;
                    text-transform: capitalize;
                    font-size: .9rem;
                    font-weight: 500;
                }
            }
        }

        .contact-us-button{
            background-color: $main-accent;
            color: #fff;
            padding: 8px 20px;
        }

    }

</style>