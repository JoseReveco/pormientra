
<template>
  <div>
    <MenuSuperior/>
    <BodyLanding/>
    <BodyInformation/>
    
  </div>
  

</template>

<script>

import MenuSuperior from '@/components/MenuSuperior.vue';
import BodyLanding from '@/components/BodyLanding.vue';
import BodyInformation from '@/components/BodyInformation.vue';


export default {
  
  name: 'HomeView',
  components: {
    MenuSuperior,
    BodyLanding,
    BodyInformation

  },
}
</script>
