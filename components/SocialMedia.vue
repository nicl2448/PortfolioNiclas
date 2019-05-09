
<script>
export default {
  props: {
    large: {
      type: Boolean,
      default: false
    }
  },

  data: () => ({
    items: [
      {
        name: 'Twitter',
        icon: 'mdi-twitter',
      },
      {
        name: 'Instagram',
        icon: 'mdi-instagram'
      },
      {
        name: 'Facebook',
        icon: 'mdi-facebook'
      },
      {
        name: 'Email',
        icon: 'mdi-email'
      },
      {
        name: 'Phone',
        icon: 'mdi-phone'
      }
    ]
  })
}
</script>
