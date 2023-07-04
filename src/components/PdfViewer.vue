<template>
  <div>
     OLA
  </div>  
</template>

<script> 

export default {  
  mounted() {
    this.openPdf()
  },
  methods: {
    openPdf() {
      const file = this.$route.params.file
      const pdfUrl = '/manifesto-da-resistencia-europeia' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
