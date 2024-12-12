<template>
    <div>
        <Hero/>
        <Benefits/>
    </div>
</template>
<script>
import Hero from '~/components/Hero.vue'
import Benefits from '~/components/Benefits.vue'
// import Destinations from '~/components/Destinations.vue'
// import Testimonials from '~/components/Testimonials.vue'
export default {
    components: { Hero, Benefits },
}
</script>
