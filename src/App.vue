<template>
  <div>
  <Head></Head>
  </div>
  <router-view/>
</template>

<style>

</style>


<script>
import Head from "@/components/Head";

export  default {
  name:"Layout",
  components:{
    Head
  }
}

</script>