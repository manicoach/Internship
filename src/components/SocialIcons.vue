<template>
  <div class="social-icons-container">
    <div class="follow-text">Follow us on our social media:</div>
    <table class="es-table-not-adapt es-social" cellspacing="0" cellpadding="0">
      <tbody>
        <tr>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://m.facebook.com/Gurukulam360DegreeLearningSchool')">
              <img title="Facebook" src="https://xniugc.stripocdn.email/content/assets/img/social-icons/circle-colored/facebook-circle-colored.png" alt="Fb" width="32">
            </a>
          </td>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://youtube.com/@gurukulamlearningschool')">
              <img title="YouTube" src="https://xniugc.stripocdn.email/content/assets/img/social-icons/circle-colored/youtube-circle-colored.png" alt="Yt" width="32">
            </a>
          </td>
          <td class="es-p10r" valign="top" align="center">
            <a target="_blank" @click="openLink('https://web.whatsapp.com/')">
              <img title="WhatsApp" src="https://xniugc.stripocdn.email/content/assets/img/social-icons/circle-colored/whatsapp-circle-colored.png" alt="WA" width="32">
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

/**<style>
.social-icons-container {
  display: grid;
  place-items: center;
  height: 100vh; /* This will make the container take the full viewport height */
}
</style>**/

<style>
.social-icons-container {
  display: flex;
  align-items: center;
  margin: 0; /* Remove default margin */
}

.follow-text {
  margin-right: 10px; /* Adjust the spacing between the text and icons */
  margin-top: 0; /* Remove top margin */
  margin-bottom: 0; /* Remove bottom margin */
  line-height: 1; /* Adjust line-height to remove*/
}

.es-p10r {
  padding-right: 10px; /* Adjust the spacing between the icons */
}
</style>




<script setup>
const { openLink } = defineProps(['openLink']);
</script>
