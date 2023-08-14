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

        <h2 class="green-heading" @click="toggleSection(1)">
        Gurukulam Mobile App Terms & Conditions 
        <span :class="{ 'arrow-down': showSection[1], 'arrow-up': !showSection[1] }"></span>
        </h2>
         <div v-if="showSection[1]">
          <h1 @click="toggleSection(2)">
            1. About these terms
            <span
              :class="{ 'arrow-down': showSection[2], 'arrow-up': !showSection[2] }"
            ></span>
          </h1>
          <div v-if="showSection[2]">
           <p>
            1.1 These terms apply to your download, access and/or use of Gurukulam on your computer, on a mobile device, on our website https://gurukulam-360-learning-school.web.app/ (the "Website") or any other website, device or platform. These terms also apply to any other services that we may provide in relation to the Gurukulam Activities or the Website, such as customer support, social media, community channels and other websites that we may operate from time to time of our Services.
            <br>
           1.2 If you do not agree to these terms or any future updated version of them then you must not access and/or use, and must cease all access and/or use of, any of our Services. If we require that any future update to these terms requires any action from you in order to accept the updated terms, then you may not be able to continue to use the Services until you have taken such action.
            <br>
           1.3 These terms represent a legal agreement between you and Gurukulam 360° Learning School any with registered office address at Door No 11-53/1, Kummara Street, Near Vinayaka Swamy Temple, Punganur-517247, Chittoor District, Andhrapradesh, India (Govt of India MSME Registered UDYAM ID -UDYAM-AP-02-0003057). The parties intend that the terms of this agreement inure to the benefit of Gurukulam’s sister, parent, subsidiary or affiliated companies.
            <br>
           1.4 In these terms references to "Gurukulam","we", "us" and "our" are references to https://gurukulam-360-learning-school.web.app/ .
            <br>
           1.5 These terms are made available via the app store or platform that you download our MGurukulam from (such as the Apple App Store, Google Play Store, Amazon App Store or Windows Phone Store), on any website or platform where you can do our Gurukulam Activities such as www.facebook.com, and on our website at https://gurukulam-360-learning-school.web.app/ (the “Website”). You agree that by accessing and/or using our Services, you are agreeing to these terms and our Privacy Policy (see paragraph 13 below).
            <br>
           1.6 For use of our Services, you agree that you are at least 13 years old and that if you are between 13 years and 18 years old, your legal guardian has reviewed and agrees to these terms and is happy for you to access and/or use our Services.
            <br>
           1.7 You can access the latest version of these terms at any time at https://gurukulam-360-learning-school.web.app/. We can make changes to these terms at any time in accordance with paragraph 17 below and, except in relation to any amendment to paragraph 21, the terms have been updated shall confirm your acceptance of the updated terms.
           </p>
          </div>
          <h1 @click="toggleSection(3)">
            2. About accessing and using our Services
            <span
              :class="{ 'arrow-down': showSection[3], 'arrow-up': !showSection[3] }"
            ></span>
          </h1>
          <div v-if="showSection[3]">
            <p>
2.1 The specific activity rules, scoring rules and guidelines for each activity can be found within the MGurukulam itself. Such rules, scoring rules and guidelines form part of these terms and you agree that you shall comply with them in respect of each individual activity which you choose to perform.
<br>
2.2 You are responsible for the internet connection and/or mobile charges that you may incur for accessing and/or using our Services. You should ask your mobile operator or internet service provider if you are unsure what these charges will be, before you access and/or use our Services.
<br>
2.3 There may be times when our Services or any part of them are not available for technical or maintenance related reasons, whether on a scheduled or unscheduled basis.
</p>
          </div>
          <h1 @click="toggleSection(4)">
            3. Accounts
            <span
              :class="{ 'arrow-down': showSection[4], 'arrow-up': !showSection[4] }"
            ></span>
          </h1>
          <div v-if="showSection[4]">
           
<p>
3.1 When using our Services you may choose to, and in some instances you will be required to, create an account with us. If you do create an account with us, you agree that you shall take all steps necessary to protect your log in details and keep them secret.
<br>
3.2 You agree that you shall not give your log in details to anyone else or allow anyone else to use your log in details or account.
<br>
3.3 In these terms, references to “log in details” or “account” include your log in details and account for any social network or platform that you may allow our Services to interact with.
<br>
3.4 We will be entitled to assume that anyone logging into your account using your log in details is either you or someone logging in with your permission. If you fail to keep your login details secret, or if you share your login details or account with someone else (whether intentionally or unintentionally), you accept full responsibility for the consequences of this (including any unauthorized purchases) and agree to fully compensate us for any losses or harm that may result.
<br>
3.5 We will not be responsible to you for any loss that you suffer as a result of an unauthorised person accessing your account and/or using our Services and we accept no responsibility for any losses or harm resulting from its unauthorised use, whether fraudulently or otherwise.
<br>
3.6 We reserve the right to delete your account if no activity is conducted by you in relation to the account for 180 or more days. In such an event, you may no longer be able to access and/or use any Virtual Money and/or Virtual Goods (as defined below) associated with that account and no refund will be offered to you in relation to the same.
<br>
3.7 You understand that if you delete your account, or if we delete your account in accordance with these terms, you may lose access to any data previously associated with your account (including, without limitation, your progress through our Activities or the level or score you have reached in our Activities any Virtual Money or Virtual Goods associated with your account).
<br>
3.8 YOU ACKNOWLEDGE AND AGREE THAT YOU SHALL HAVE NO OWNERSHIP OR OTHER PROPERTY INTEREST IN ANY ACCOUNT THAT YOU CREATE USING ANY OF OUR SERVICES. WE MAY SUSPEND, TERMINATE, MODIFY OR DELETE ANY OF THESE ACCOUNTS AT ANY TIME FOR ANY REASON OR NO REASON, WITH OR WITHOUT NOTICE TO YOU.
<br>
3.9 Your account is personal to you and you are not entitled to transfer your account to any other person.
</p>
          </div>
          <h1 @click="toggleSection(5)">
            4. Virtual Goods and Virtual Money
            <span
              :class="{ 'arrow-down': showSection[5], 'arrow-up': !showSection[5] }"
            ></span>
          </h1>
          <div v-if="showSection[5]">
           
<p>
4.1 Our activities may include virtual currencies such as Gold, Silver, Bronze and Green Stars (Virtual Money), items or services for use with our activities (“Virtual Goods"). You may first have to reach a certain level or progress to a certain point. You agree that once purchased Virtual Money and Virtual Goods have no monetary value and can never be exchanged for real money, real goods or real services from us or anyone else. You agree that Virtual Money and Virtual Goods are not transferrable to anyone else and you will not transfer or attempt to transfer any Virtual Money and Virtual Goods. If in case you want to donate your virtual money and virtual goods then its subjected to the approval from Gurukulam.
<br>
4.2 You do not own Virtual Goods, Virtual Money but instead you purchase any educational item.
<br>
4.3 You agree that all sales by us to you of Virtual Money and/or Virtual Goods are final, that we will not refund any transaction once it has been made. A"purchase" is complete at the time our servers validate your purchase and the applicable Virtual Goods and/or Virtual Money are successfully credited to your account on our servers.
<br>
4.4 If you do not connect your activity on a device to an account that is linked to either your social network account or a Gurukulam account, we will not be able to restore any Virtual Money or other data associated with your activity to a different device if you lose that device or it is damaged. Accordingly, on a device which is not connected in this way:
<ul>
    <li>any risk of loss of Virtual Money which you purchase from us is transferred to you upon completion of the purchase as described in paragraph 4.3 above;</li>
    <li>any risk of loss of Virtual Money that you receive from us without making a purchase is transferred to you at the time the Virtual Money is successfully credited to your account on our servers; and </li>
    <li>any risk of loss of other data associated with your activity (including, without limitation, your progress through the activity, or the level or score you have reached in our activities) is transferred to you immediately at the time such activities data is generated.</li>
</ul>

4.5 The data associated with Virtual Goods, whether purchased by you using Virtual Money or otherwise credited or awarded to you, is stored locally on your device and so is not synced between different devices even if you have connected your activities on a device to an account that is linked to either your social network account or Gurukulam account. Accordingly, any risk of loss of this data is transferred to you (i) in the case of Virtual Goods which you purchase from us, upon completion of the purchase as described in paragraph 4.3 above; and/or (ii) in other cases, at the time the Virtual Goods are credited or awarded to you.
<br>
4.6 You agree that the invoices may be electronic in format.
<br>
4.7 We reserve the right to control, regulate, change or remove any Virtual Money, Virtual Goods without any liability to you at any time, but if you are an active user such changes will only take effect following the end of the inactive period, at which 180 days inactive period will automatically terminate.
<br>
4.8 We may revise the pricing for Virtual Goods, Virtual Money offered through the Services at any time. You are only allowed to obtain Virtual Money and Virtual Goods from us or our authorized partners through the Services, and not in any other way.
<br>
4.9 Depending on your platform, any Virtual Goods, Virtual Money or Subscriptions purchased may be subject to your platform provider's terms of service and user agreement. Usage rights for each purchase may differ from item to item. If you are unsure about usage rights you should check with your platform or our customer support team before making a purchase.
<br>
4.10 Without limiting paragraphs 3.7, 4.4 or 7.1 if we suspend or terminate your account in accordance with these terms you may lose any Virtual Money, and Virtual Goods (see paragraph 4.12) that you may have and we will not compensate you for this loss or make any refund to you.
<br>
4.11 The charge for any individual item you can purchase via our Website shall be as stated on our Website at the time you place the order, except in the case of obvious error.
<br>
User Inactivity
<br>
4.12 Any user inactive for 180 Days are above will be terminated and all their data will be cancelled. They need to activate the account again to do the activities and use our services
</p>
           
          </div>
          <h1 @click="toggleSection(6)">
            5. User conduct and content
            <span
              :class="{ 'arrow-down': showSection[6], 'arrow-up': !showSection[6] }"
            ></span>
          </h1>
          <div v-if="showSection[6]">
           <p>
5.1 You must comply with the laws that apply to you in the location that you access our Services from. If any laws applicable to you restrict or prohibit you from using our Services, you must comply with those legal restrictions or, if applicable, stop accessing and/or using our Services.
<br>
5.2 You promise that all the information you provide to us on accessing and/or using our Services is and shall remain true, accurate and complete at all times.
<br>
5.3 Information, data, software, sound, photographs, graphics, video, messages, tags, or other materials may be sent, uploaded, communicated, transmitted or otherwise made available via our Services by you or another user (“Content”). You understand and agree that all Content that you may be sent when using our Services, whether publicly posted or privately sent, is the sole responsibility of the person that sent the Content. This means that you, not us, are entirely responsible for all Content that you may upload, communicate, transmit or otherwise make available via our Services.
<br>
5.4 You agree not to upload, communicate, transmit or otherwise make available any Content or otherwise use the Services in any way:
<ul>
    <li>that is or could reasonably be viewed as unlawful, harmful, harassing, defamatory, libellous, obscene or otherwise objectionable;</li>
    <li>that is or could reasonably be viewed as invasive of another's privacy or violate any privacy rights;</li>
    <li>that is likely to, or could reasonably be viewed as likely to incite violence or racial or ethnic hatred;</li>
    <li>which you do not have a right to make available lawfully (such as inside information, information which belongs to someone else or confidential information);</li>
    <li>which infringes any intellectual property right or other proprietary right of others;</li>
    <li>which consists of any unsolicited or unauthorised advertising, promotional materials, 'junk mail', 'spam', 'chain letters', 'pyramid schemes' or any other form of solicitation; or</li>
    <li>which contains software viruses or any other computer code, files or programs designed to interrupt, destroy or limit the functionality of any computer software or hardware or telecommunications equipment.</li>
</ul>
5.5 You agree that you will not:
<ul>
    <li>use our Services to harm anyone or to cause offence to or harass any person;</li>
    <li>create more than one account per platform to access our Services;</li>
    <li>use another person or entity’s email address in order to sign up to use our Services;</li>
    <li>use our Services for fraudulent or abusive purposes (including, without limitation, by using our Services to impersonate any person or entity, or otherwise misrepresent your affiliation with a person, entity or our Services);</li>
    <li>disguise, anonymise or hide your IP address or the source of any Content that you may upload;</li>
    <li>use our Services for any commercial or business purpose or for the benefit of any third party or to send unsolicited communications;</li>
    <li>remove or amend any proprietary notices or other ownership information from our Games or any other part of our Services;</li>
    <li>interfere with or disrupt our Services or servers or networks that provide our Services;</li>
    <li>attempt to decompile, reverse engineer, disassemble or hack any of our Services, or to defeat or overcome any of our encryption technologies or security measures or data transmitted, processed or stored by us;</li>
    <li>'harvest', 'scrape' or collect any information about or regarding other people that use our Services, including, but not limited to any personal data or information (including by uploading anything that collects information including but not limited to 'pixel tags' cookies, graphics interchange formats ('gifs') or similar items that are sometimes also referred to as 'spyware' or 'pcms' (passive collection mechanisms);</li>
    <li>sell, transfer or try to sell or transfer an account with us or any part of an account, Virtual Money and/or Virtual Goods;</li>
    <li>disrupt the normal flow of an activity or otherwise act in a manner that is likely to negatively affect other users' ability to compete fairly when performing our activities or engaging in real time exchanges;</li>
    <li>disobey any requirements or regulations of any network connected to our Services;</li>
    <li>use our Services in violation of any applicable law or regulation;</li>
    <li>use our Services to cheat or design or assist in cheating (for example, by using automated means or third party software to play), or to otherwise circumvent technological measures designed to control access to, or elements of, our Services, or to do anything else that a reasonable person is likely to believe is not within the spirit of fair play or these terms; or</li>
    <li>use our Services in any other way not permitted by these terms.</li>
</ul>
If you are concerned that someone else is not complying with any part of these terms, please contact us here: gurukulamlearningschool@gmail.com
<br>
5.6 We do not control Content posted on our Services by other people and therefore we do not guarantee the accuracy, integrity or quality of that Content. You understand that when using our Services, you may be exposed to Content that you may consider offensive, indecent or objectionable. Under no circumstances will we be liable in any way for any Content, including, but not limited to, any errors or omissions in any Content, or any losses or harm of any kind resulting from the use of any Content posted, emailed, transmitted or otherwise made available via our Services.
<br>
5.7 We have the right to remove uploaded Content from our Services if we decide in our sole discretion that it results in or from a breach of any part of these terms, or that it may bring us or our Services into disrepute. However, you acknowledge that we do not actively monitor Content that is contributed by people that use our Services and we make no undertaking to do so.
<br>
5.8 You are solely responsible for your interactions with other users of our Services. You agree that you shall not hold Gurukulam liable for any loss or damage arising from the Content (yours or another user's) including without limitation in respect of any defamation, harassment, or false endorsement claims.
</p>
          </div>
          <h1 @click="toggleSection(7)">
            6. Intellectual Property
            <span
              :class="{ 'arrow-down': showSection[7], 'arrow-up': !showSection[7] }"
            ></span>
          </h1>
          <div v-if="showSection[7]">
           <p>
6.1 You acknowledge that all copyright, trade marks, and other intellectual property rights in and relating to our Services (other than Content which is contributed and owned by users) is owned by or licensed to us.
<br>
6.2 Whilst you are in compliance with these terms, we grant you a non-exclusive, non-transferable, personal, revocable limited licence to access and/or use our Services (but not any related object and source code) for your own personal private use, in each case provided that such use is in accordance with these terms. You agree not to use our Services for anything else. These terms also apply to any update or patches which we may release or make available for any of the Services and any such update or patch shall be deemed part of the Services for the purposes of these terms.
<br>
6.3 YOU ACKNOWLEDGE AND AGREE THAT, OTHER THAN LICENSE GRANTED TO YOU BY THESE TERMS, YOU SHALL HAVE NO OWNERSHIP OR PROPERTY INTEREST IN ANY OF OUR SERVICES, INCLUDING WITHOUT LIMITATION ONLINE ACCOUNTS, ANY VIRTUAL MONEY OR VIRTUAL GOODS. You must not copy, distribute, make available to the public or create any derivative work from our Services or any part of our Services unless we have first agreed to this in writing.
<br>
6.4 In particular, and without limiting the application of paragraph 6.3, you must not make use or available any cheats or technological measures designed to control access to, or elements of, our Services, including providing access to any Virtual Money and/or Virtual Goods, whether on a free of charge basis or otherwise.
<br>
6.5 By submitting Content (as defined in paragraph 5.3) via our Services you:
<ul>
<li>are representing that you are fully entitled to do so;</li>
<li>grant us and our group companies the right to edit, adapt, publish and use your entry and any derivative works we may create from it, in any and all media (whether it exists now or in the future), for any purpose, in perpetuity, without any payment to you;</li>
<li>acknowledge that you may have what are known as “moral rights” in the Content, for example the right to be named as the creator of your entry and the right not to have work subjected to derogatory treatment. You agree to waive any such moral rights you may have in the Content; and</li>
<li>agree that we have no obligation to monitor or protect your rights in any Content that you may submit to us, but you do give us the right to enforce your rights in that Content if we want to, including but not limited to taking legal action (at our cost) on your behalf.</li>
</ul>
6.6 You must not copy, distribute, make available to the public or create any derivative work from any Content belonging to any other user of our Services. If you believe that your intellectual property rights have been infringed by someone else over the internet, you may contact us by emailing the following information to gurukulamlearningschool@gmail.com:
<ul>
<li>a description of the intellectual property rights and an explanation as to how they have been infringed;</li>
<li>a description of where the infringing material is located;</li>
<li>your address, phone number and email address;</li>
<li>a statement by you, made under penalty of perjury, that (i) you have a good-faith belief that the disputed use of material in which you own intellectual property rights is not authorised, and (ii) the information that you are providing is accurate, correct, and that you are authorised to act on behalf of the owner of an exclusive right that is allegedly infringed; and</li>
<li>a physical or electronic signature of the person authorised to act on behalf of the owner of the exclusive right that has allegedly been infringed.</li>
</ul>
</p>

          </div>
          <h1 @click="toggleSection(8)">
            7. Privacy
            <span
              :class="{ 'arrow-down': showSection[8], 'arrow-up': !showSection[8] }"
            ></span>
          </h1>
          <div v-if="showSection[8]">
           
<p>
7.1 The data controller for all personally identifiable information or personal data that we collect about you through or in relation to our activities or other Services is https://gurukulam-360-learning-school.web.app/.
<br>
7.2 https://gurukulam-360-learning-school.web.app/ collect, process, use and share your personal information in accordance with our Privacy Policy and as set out in these terms. If you do not agree to our Privacy Policy you should not download or access our activities or otherwise access and/or use our Services.
<br>
7.3 This paragraph 13 shall not affect the provisions of paragraphs 20 and 21 which shall take precedence over this paragraph 13.
</p>

          </div>
          <h1 @click="toggleSection(9)">
            8. Links
            <span
              :class="{ 'arrow-down': showSection[9], 'arrow-up': !showSection[9] }"
            ></span>
          </h1>
          <div v-if="showSection[9]">
                     
<p>
8.1 We may link to third party websites or services from our Services. You understand that we make no promises regarding any content, goods or services provided by such third parties and we do not endorse the same. We are also not responsible to you in relation to any losses or harm caused by such third parties. Any charges you incur in relation to those third parties are your responsibility. You understand that when you provide data to such third parties you are providing it in accordance with their privacy policy (if any) and our own privacy policy does not apply in relation to that data.
</p>

          </div>
          <h1 @click="toggleSection(10)">
            9. Transferring these terms
            <span
              :class="{ 'arrow-down': showSection[10], 'arrow-up': !showSection[10] }"
            ></span>
          </h1>
          <div v-if="showSection[10]">
          <p>
9.1 We may wish to transfer all or a part of our rights or responsibilities under these terms to someone else without obtaining your consent. You agree that we may do so provided that the transfer does not significantly disadvantage you. You may not transfer any of the rights we give you under these terms unless we first agree to this in writing.
</p>

          </div>
          <h1 @click="toggleSection(11)">
            10. Entire agreement
            <span
              :class="{ 'arrow-down': showSection[11], 'arrow-up': !showSection[11] }"
            ></span>
          </h1>
          <div v-if="showSection[11]">
           <p>
10.1 These terms set out the entire agreement between you and us concerning our Services (as defined in paragraph 1) and they replace all earlier agreements and understandings between you and us.
</p>
   
          </div>
          <h1 @click="toggleSection(12)">
            11. Changes to these terms
            <span
              :class="{ 'arrow-down': showSection[12], 'arrow-up': !showSection[12] }"
            ></span>
          </h1>
          <div v-if="showSection[12]">
           <p>
11.1 You can find these terms at any time by visiting https://gurukulam-360-learning-school.web.app/.
<br>
11.2 Without affecting paragraph 21.8 below, we reserve the right to update these terms from time to time by posting the updated version at that address. We may do so for a number of reasons including without limitation because we change the nature of our products or services, for technical or legal reasons, or because the needs of our business have changed. You agree that if you do not accept any amendment to our terms then you shall immediately stop accessing and/or using our Services.
</p>
          </div>
          
          <h1 @click="toggleSection(13)">
            12. Severability
            <span
              :class="{ 'arrow-down': showSection[13], 'arrow-up': !showSection[13] }"
            ></span>
          </h1>
          <div v-if="showSection[13]">
           <p>
12.1 If any part of these terms is held to be invalid or unenforceable under any applicable local laws or by an applicable court, that part shall be interpreted in a manner consistent with applicable law to reflect as nearly as possible our original intentions and the remainder of these terms shall remain valid and enforceable. If it is not possible to interpret an invalid or unenforceable part of these terms in a manner consistent with applicable law, then that part shall be deemed deleted from these terms without affecting the remaining provisions of these terms.
</p>
          </div>
          <h1 @click="toggleSection(14)">
            13. Waivers of our rights
            <span
              :class="{ 'arrow-down': showSection[14], 'arrow-up': !showSection[14] }"
            ></span>
          </h1>
          <div v-if="showSection[14]">
           <p>
13.1 Our failure to exercise or enforce any of our rights under these terms does not waive our right to enforce such right. Any waiver of such rights shall only be effective if it is in writing and signed by us.
</p>

          </div>
          <h1 @click="toggleSection(15)">
            14. Complaints and dispute resolution
            <span
              :class="{ 'arrow-down': showSection[15], 'arrow-up': !showSection[15] }"
            ></span>
          </h1>
          <div v-if="showSection[15]">
           <p>
14.1 Most concerns can be solved quickly by contacting us at gurukulamlearningschool@gmail.com.
<br>
14.2 In the unlikely event that we cannot solve your concern and you wish to bring legal action against us these terms shall be governed by and construed in accordance with the laws of India.

         </p>

          </div>
          <p>
          By clicking "I agree" or by accessing and using the Gurukulam Mobile App, you acknowledge that you have read, understood, and agree to be bound by the following terms and conditions. If you do not agree to these terms, please do not use the app.

<br>1. You agree to comply with all applicable laws and regulations while using the Gurukulam Mobile App.

<br>2. You acknowledge that the Gurukulam Mobile App may collect and use your personal information in accordance with our Privacy Policy.

<br>3. You understand that the Gurukulam Mobile App may use cookies and similar technologies to enhance your user experience.

<br>4. Any content you submit or create within the Gurukulam Mobile App is your sole responsibility, and you grant us the right to use, modify, and distribute such content.

<br>5. The Gurukulam Mobile App reserves the right to modify, suspend, or terminate the app's services at any time.

<br>6. You agree not to reverse engineer, decompile, or modify any part of the Gurukulam Mobile App.

<br>7. In no event shall the Gurukulam Mobile App be liable for any direct, indirect, incidental, or consequential damages.

<br>8. Disputes arising from the use of the Gurukulam Mobile App shall be governed by the laws of your jurisdiction, and you consent to the exclusive jurisdiction of the courts in your jurisdiction.

<br>Please review our full Terms and Conditions and Privacy Policy for more details. Your use of the Gurukulam Mobile App is subject to these terms and policies.

<br>By clicking "I agree," you indicate that you have read, understood, and agree to these terms and conditions. If you have any questions, please contact us at [Contact Email Address].
</p>
 

<div class="checkbox-container">
  <input type="checkbox" id="agreeCheckbox">
  <label for="agreeCheckbox">I agree to the Terms and Conditions</label>
</div>
<div class="proceed-container">
  <button id="proceedButton" disabled>Proceed</button>
</div>



        </div>  
       </ion-col>
      </ion-row>
     </ion-grid>  


      <ExploreContainer name="" />
    </ion-content>
  </ion-page>
</template>

<style>
  .banner-img{
  width: 100%;
} 
  /* Add styles for the arrows */
  .arrow-down::after {
    content: "\25BC"; /* Down arrow unicode character */
    margin-left: 5px;
  }

  .arrow-up::after {
    content: "\25B2"; /* Up arrow unicode character */
    margin-left: 5px;
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
    color: black;
    margin-bottom: 16px;
  }
  h1{
    font-family: 'Lato', sans-serif;
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 16px;
  }
  p{
    font-family: 'Lato', sans-serif;
    font-size: 16px;
    line-height: 1.6;
  }
  .checkbox-container {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 16px;
}

.proceed-container {
  display: flex;
  align-items: center;
  justify-content: center;
}

#proceedButton: {
  background-color: #b0ba6e;
  border-radius: 10px;
  padding: 8px 16px;
  font-family: 'Lato', sans-serif;
  font-size: 20px;
  font-weight: bold;
  color: #fff;
  cursor: not-allowed;
  border: none;
  outline: none;
}

#proceedButton:enabled{
  background-color: #b0c23e;
  cursor: pointer;
  border-radius: 10px;
  padding: 8px 16px;
  font-family: 'Lato', sans-serif;
  font-size: 20px;
  font-weight: bold;
  color: #fff;
  cursor: not-allowed;
  border: none;
  outline: none;
}

</style>


<script setup lang="ts">
import { ref } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

const showSection = ref({
  1: false,
  2: false,
  3: false, 
  4: false,
  5: false,
  6: false,
  7: false,
  8: false,
  9: false,
  10: false,
  11: false,
  12: false,
  13: false,
  14:false,
  15: false,// Initialize each section to be collapsed initially
});

// Function to toggle the display of each section when the heading is clicked
const toggleSection = (sectionNumber) => {
  showSection.value[sectionNumber] = !showSection.value[sectionNumber];
};

document.addEventListener("DOMContentLoaded", function() {
  const agreeCheckbox = document.getElementById("agreeCheckbox");
  const proceedButton = document.getElementById("proceedButton");

  agreeCheckbox.addEventListener("change", function() {
    if (this.checked) {
      enableButton(); // Enable the button
    } else {
      disableButton(); // Disable the button
    }
  });
  function enableButton() {
    proceedButton.classList.add('enabled');
    proceedButton.removeAttribute('disabled');
  }

  function disableButton() {
    proceedButton.classList.remove('enabled');
    proceedButton.setAttribute('disabled', 'disabled');
  }

  proceedButton.addEventListener("click", function() {
    // Redirect or navigate to Tab 3
    // Replace this with the actual code to navigate to Tab 3
    // For example: window.location.href = "tab3.html" ;
  });
});

</script>