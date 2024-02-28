<template>
  <div class="home">
    
    <HeaderComponent />

    <ReasonComponent />

    <AppComponent />

    <ContactComponent />

  </div>
</template>


<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import ReasonComponent from '@/components/ReasonSection.vue';
import AppComponent from '@/components/AppComponent.vue';

import ContactComponent from '@/components/ContactComponent.vue';

export default {

  components: {
    HeaderComponent,
    ReasonComponent,
    AppComponent,

    ContactComponent
  }

}

</script>