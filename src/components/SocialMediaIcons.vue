<template>
  <ion-grid>
    <ion-row>
      <ion-col size="4">
        <a @click="openSocialMedia(platform.url)">
          <ion-icon :name="platform.iconName"></ion-icon>
        </a>
      </ion-col>
    </ion-row>
  </ion-grid>
</template>

<script setup>
const socialMediaPlatforms = [
  {
    name: 'YouTube',
    iconName: 'logo-youtube',
    url: 'https://youtube.com/@gurukulamlearningschool', // Replace with your YouTube URL
  },
  {
    name: 'Facebook',
    iconName: 'logo-facebook',
    url: 'https://m.facebook.com/Gurukulam360DegreeLearningSchool/', // Replace with your Facebook URL
  },
  {
    name: 'WhatsApp',
    iconName: 'logo-whatsapp',
    url: 'https://web.whatsapp.com/', // Replace with your WhatsApp URL
  },
];

const openSocialMedia = (url) => {
  window.open(url, '_blank');
};
</script>

<style scoped>
/* Custom styles for the icon links */
a {
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  color: #ffffff; 
  font-size: 24px; 
  height: 48px; 
  width: 48px; 
}
</style>
