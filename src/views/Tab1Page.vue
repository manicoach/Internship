<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
     <ion-grid>
      <ion-row>
       <ion-col>
        <!-- Banner -->
        <img src="../assets/banner.png" alt="Banner Image" class="banner-img" />

        <!-- Mission Statement -->
        <div class="mission">
         <h2 class="green-heading">Mission</h2>
         <p>
          <h1>"Children are the world's most valuable resource and its best hope for the future." </h1>
          Our mission is to empower every child to become a champion through our innovative Experiential Learning Methodology. 
          <br>
          We are committed to creating an environment where students can effectively learn, practice, and enhance their skills by using scientifically proven concepts within our Tiny Habits model.
          
          <br> 
          By engaging in simple yet impactful activities, we aim to facilitate holistic growth and development in every student."
          
         </p>
         <h2 class="green-heading"> Our Activities </h2>
         <p>
          Here are some of our recommended activities:
          <ul>
          <li>5AM Club Braingym</li>
          <li>6AM Club Happiness DOSE</li>
          <li>7AM Club Chakra Healing Meditation</li>
          <li>8AM Club Energy Breathing Exercises</li>
          <li>7PM Club Reflection Guided Meditation</li>
          <li>Yoga Nidra</li>
          <li>Zero Budget Treatment</li>
          </ul>
         </p>
        </div>

        <!-- Social Media Icons -->
        <div>
          <SocialIcons :openLink="openLink" />
        </div>

        <!-- YouTube Link -->
        <div class="youtube-link">
         <h2>YouTube</h2>
         <a href="https://youtube.com/@gurukulamlearningschool" target="_blank">
           Watch our videos on YouTube
         </a>
        </div>

        <!-- Facebook Feed Link -->
        <div class="facebook-link">
         <h2> Facebook </h2>
         <a href="https://m.facebook.com/Gurukulam360DegreeLearningSchool/" target="_blank">
           Visit our Facebook page
         </a>
        </div>
       </ion-col>
      </ion-row>
     </ion-grid>  
      <ExploreContainer name="" />
    </ion-content>
  </ion-page>
</template>



<style>
/* Custom styles */
.banner-img{
  width: 100%;
} 
.green-heading {
  background-color: #b0c23e;
  border-radius: 10px;
  padding: 8px 16px;
  font-family: 'Lato', sans-serif;
  font-size: 34px;
  font-weight: bold;
  color: #fff;
  margin-bottom: 16px;
}

  h2{
    font-family: 'Lato', sans-serif;
    font-size: 34px;
    font-weight: bold;
    margin-bottom: 0;
    color: #4a9475;
    padding: 0;
  }
  p{
    font-size: 20px;
    line-height: 1.6;
  }
  .mission h1{
    font-size: 20px;
    color: black; /* You can customize the color for each class if needed */
    font-weight: bold;
}

  .content {
  background-color: #b0f5d3;
}
</style>


<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
import { defineProps } from 'vue';
import SocialIcons from '../components/SocialIcons.vue';

import { openLink } from '../utils/openLink';

// You can also define openLink directly in this component if needed.

const props = defineProps();

//import SocialMediaIcons from '@/components/SocialMediaIcons.vue';
</script>
