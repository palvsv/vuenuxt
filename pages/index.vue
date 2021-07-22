<template>
  <div>
    <Banner />
    <Service />
    <FeaturesOne />
    <FeaturesTwo />
    <Video />
    <Counter />
    <Pricing />
    <Screenshots />
    <Testimonial />
    <Brands />
    <Faq />
    <BlogHome />
    <Contact />
    <CallToAction />
  </div>
</template>

<script>
  import Banner from "~/components/Banner.vue";
  import Service from "~/components/Service.vue";
  import FeaturesOne from "~/components/FeaturesOne.vue";
  import FeaturesTwo from "~/components/FeaturesTwo.vue";
  import Video from "~/components/Video.vue";
  import Counter from "~/components/Counter.vue";
  import Pricing from "~/components/Pricing.vue";
  import Screenshots from "~/components/Screenshots.vue";
  import Testimonial from "~/components/Testimonial.vue";
  import Brands from "~/components/Brands.vue";
  import Faq from "~/components/Faq.vue";
  import BlogHome from "~/components/BlogHome.vue";
  import Contact from "~/components/Contact.vue";
  import CallToAction from "~/components/CallToAction.vue";

export default {
  components: {
    Banner,
    Service,
    FeaturesOne,
    FeaturesTwo,
    Video,
    Counter,
    Pricing,
    Screenshots,
    Testimonial,
    Brands,
    Faq,
    BlogHome,
    Contact,
    CallToAction

  }
}
</script>

<style>

</style>
