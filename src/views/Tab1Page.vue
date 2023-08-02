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
         <h2>Mission Statement</h2>
         <p>
          Our mission is to make every child a champion through our Experiental Learning Methodology.
          <br>
          We help students to learn,practice and strengthen their skills through scientifically proven concepts in our Tiny Habits model.
          <br> 
          We train students in simple activities that will lead to their holistic growth and development. 
          <br>
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

.mission h2,
.youtube-link h2,
.facebook-link h2

.mission p,
.youtube-link a,
.facebook-link a {
  font-size: 16px;
  line-height: 1.6;
  margin: 0; /* Remove the default margin */
  padding: 0; /* Remove the default padding */
}

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
import { defineProps } from 'vue';
import SocialIcons from '../components/SocialIcons.vue';

import { openLink } from '../utils/openLink';

// You can also define openLink directly in this component if needed.

const props = defineProps();

//import SocialMediaIcons from '@/components/SocialMediaIcons.vue';
</script>
