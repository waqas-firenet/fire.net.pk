<template>
  <div class="home">
    
    <HeaderComponent />

    <ReasonComponent />

    <AppComponent />

    <FeaturesComponent />

    <PricingComponent />

    <TeamComponent />

    <ContactComponent />

  </div>
</template>


<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import ReasonComponent from '@/components/ReasonSection.vue';
import AppComponent from '@/components/AppComponent.vue';
import FeaturesComponent from '@/components/FeaturesComponent.vue';
import PricingComponent from '@/components/PricingComponent.vue';
import TeamComponent from '@/components/TeamComponent.vue';
import ContactComponent from '@/components/ContactComponent.vue';

export default {

  components: {
    HeaderComponent,
    ReasonComponent,
    AppComponent,
    FeaturesComponent,
    PricingComponent,
    TeamComponent,
    ContactComponent
  }

}

</script>