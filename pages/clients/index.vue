<template lang="pug">

    div
        section.uk-section
            .uk-container
                .case-header-content
                    p.uk-margin-remove What we do #[span(uk-icon="icon: arrow-right; ratio: 0.75;")]
                    h1.uk-heading-small.uk-margin-remove(class="uk-width-xlarge@m") All work, all play
                    h2.uk-heading-small.uk-margin-remove From startups to industry leaders
                    p(class="uk-width-xlarge@m") We like our clients. We like helping them seize opportunities and find solutions. They are friends and co-conspirators. Together we build ideas, and build on those ideas.

        section.uk-section
            .uk-container
                ul.tab-container(uk-tab="animation: uk-animation-slide-top-small")
                    li 
                        a Web Design
                    li
                        a Ecommerce
                    li
                        a Startups

                ul(class="uk-switcher uk-margin")
                    li(v-for="index in 3")
                        div.gallery-list
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fd483c111-2cbb-4a6a-8a99-5ae8e9c38f64_city-2.png?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove Google
                                    p.uk-margin-remove Diseño Web
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fd483c111-2cbb-4a6a-8a99-5ae8e9c38f64_city-2.png?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove Facebook
                                    p.uk-margin-remove Planificación de Campaña Corporativa
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fa83b7acf-66b1-4d1c-ac32-7dde7cab9c37_dorsia_wildposting_kn_03.jpg?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://ueno.co/static/9930d93b0a4d7a1b8a0f8c25c253cbe9/8fc1f/30a872c9-ec6d-4da8-a40e-cf597409cb05_Cowboy1200x1200.webp")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://ueno.co/static/72299ba88c8105be346665e058b42e0b/e7405/ca3d4561-c5b2-4e99-8147-f916251f451f_uber-thumb.webp")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    video(src="https://ueno.co/static/whyyy-e6dafee39c66938d729d5abb5a243795.mp4",  autoplay, loop, muted, playsinline)
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fa83b7acf-66b1-4d1c-ac32-7dde7cab9c37_dorsia_wildposting_kn_03.jpg?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fa83b7acf-66b1-4d1c-ac32-7dde7cab9c37_dorsia_wildposting_kn_03.jpg?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general
                            div
                                nuxt-link.uk-display-inline-block(to="/clients/cases/test")
                                    img(src="https://images.prismic.io/ueno-www%2Fa83b7acf-66b1-4d1c-ac32-7dde7cab9c37_dorsia_wildposting_kn_03.jpg?auto=compress,format")
                                .uk-margin-top
                                    h4.uk-margin-remove RedCollege
                                    p.uk-margin-remove Apoyo a la empresa general

                    
    
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    .tab-container{
        li{
            a{
                font-family: $title-font;
                text-transform: capitalize;
            }
        }
    }

    .case-header-content{
        margin-left: 40%;
    }

    .gallery-list{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
        grid-template-rows: auto;
        grid-gap: 3rem;
        grid-auto-flow: dense;
        div:nth-child(3n){
            grid-column: span 2;
            grid-row: span 2;
        }

        p{
            font-size: .9rem;
            line-height: 1.2rem;
        }

    }

</style>