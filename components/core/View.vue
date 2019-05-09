<template>
  <div>
    <welcome />
    <services />
    <MineProjekter />
    <about-me />
  </div>
</template>

<script>
export default {
  components: {
    AboutMe: () => import('@/components/AboutMe'),
    MineProjekter: () => import('@/components/MineProjekter'),
    Services: () => import('@/components/Services'),
    Welcome: () => import('@/components/Welcome')
  }
}
</script>
