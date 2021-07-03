<template>
  <div>
    <header-app />
    <Nuxt />
    <footer-app />
  </div>
</template>

<script>
import Header from "@/components/common/header";
import Footer from "@/components/common/footer";
export default {
  components: {
    'header-app': Header,
    'footer-app': Footer
  }

}
</script>
