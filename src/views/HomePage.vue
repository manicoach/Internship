<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Home</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true" class="ion-padding">
      <h2>Welcome to the app</h2>
      <p>
         This is the home page content. Purpose, youtube video, facebook feeds, whatsapp group.
         Gurukulam Tiny Habits Routines
         5AM Club Braingym
         6AM Club Happiness DOSE
         7AM Club Chakra Healing Meditation
         8AM Club Energy Breathing Exercises
         7PM Club Reflection Guided Meditation
         Yoga Nidra
         Zero Budget Treatment
      </p> 


      <ExploreContainer name="Home page" />
    </ion-content>
  </ion-page>
</template>

<style>
  h2{
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 16px;
  }
  p{
    font-size: 16px;
    line-height: 1.6;
  }
</style>


<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
