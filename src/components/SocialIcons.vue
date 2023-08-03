<template>
  <div class="social-icons-container">
    <div class="follow-text">Follow us on our social media:</div>
    <table class="es-table-not-adapt es-social" cellspacing="0" cellpadding="0">
      <tbody>
        <tr>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://m.facebook.com/Gurukulam360DegreeLearningSchool')">
              <img title="Facebook" src="@/assets/facebook-icon.png" alt="Fb" class="circular-icon">
            </a>
          </td>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://youtube.com/@gurukulamlearningschool')">
              <img title="YouTube" src="@/assets/youtube-icon.png" alt="Yt" class="circular-icon">
            </a>
          </td>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://web.whatsapp.com/')">
              <img title="WhatsApp" src="@/assets/whatsapp-icon.png" alt="WA" class="circular-icon">
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>


<style>
.social-icons-container {
  display: flex;
  align-items: center;
  margin: 0;
  padding: 10px; /* Remove default margin */
  background-color: #b0c23e;
  border-radius: 10px;
  color: #fff;
}

.follow-text {
  margin-right: 20px; /* Adjust the spacing between the text and icons */
  margin-top: 0; /* Remove top margin */
  margin-bottom: 0; /* Remove bottom margin */
  line-height: 1.6; /* Adjust line-height to remove*/
  font-family: 'Lato', sans-serif;
  font-size: 24px;
}

.es-p10r {
  padding-right: 10px; /* Adjust the spacing between the icons */
}
/* Override the styles for circular icons */
.circular-icon {
  border-radius: 50%; /* Make the image circular */
  width: 64px;
  border: none;
}
</style>




<script setup>
const { openLink } = defineProps(['openLink']);
</script>
