<template>
<div>
  <v-container fluid>
    <v-btn flat color="white" class="logo"><img src="../assets/logo_white.png" /> Gomusu</v-btn>
    <v-layout
      text-xs-center
      wrap
      class="main"
    >
      <v-flex mb-4>
        <h1 class="display-2 font-weight-bold mb-3">
          The easiest way to support a specific musician on Youtube.
        </h1>
        <p class="subheading font-weight-regular">
          Choose a specific person. Choose the specific person. Support in one-click. Keep the music going.
        </p>

<!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup">
<form action="https://gomusu.us17.list-manage.com/subscribe/post?u=ea83671015743a0a68746f45e&amp;id=df7a38b83b" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
   <div id="mc_embed_signup_scroll">
    <div class="mc_signup">
    <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="Your email address" required>
   <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
   <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_ea83671015743a0a68746f45e_df7a38b83b" tabindex="-1" value=""></div>
   <div class="clear"><input type="submit" value="I WANT TO SUPPORT" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
   </div>
   </div>
</form>
</div>

      </v-flex>

    </v-layout>
  </v-container>

  <v-container fluid text-xs-center class="personas">
    <h1 class="display-2 font-weight-bold mt-5">Why Gomusu?</h1>
    <v-layout wrap row class="mt-4">
      <v-flex sm12 md4><img src="../assets/img_1.png" /></v-flex>
      <v-flex sm12 md8>
        <h1 class="mt-5">Easy, one-click tip directly from Chrome</h1>
        <p>
          Listen as you’re used to.
          Click on ‘Tip’ to support the musician(s) you’re listening to! Click on ‘C-Tip’ for a custom tip:
          You can choose the Tip amount, its frequency and for the first time...
        </p>
      </v-flex>
    </v-layout>
    <v-layout wrap row reverse class="mt-4">
      <v-flex sm12 md4><img src="../assets/img_2.png" /></v-flex>
      <v-flex sm12 md8>
        <h1 class="mt-5">You can pick exactly who you want to support</h1>
        <p>
          Does the singer gets it all or is it all about that bass? You choose.
          Gomusu lets you tip your favorite band, band member or solo artist.
          Whoever you choose your tip does matter because...
        </p>
      </v-flex>
    </v-layout>
    <v-layout wrap row class="mt-4">
      <v-flex sm12 md4><img src="../assets/img_3.png" /></v-flex>
      <v-flex sm12 md8>
        <h1 class="mt-5">We Cut the middlemen</h1>
        <p>
          Your musician(s) of choice gets 96% of the tip. No record company or distributor fee. No parasite uploader.
          We keep 4% to cover transaction fees and make Gomusu even more awesome.
        </p>
      </v-flex>
    </v-layout>
    <v-layout wrap row reverse class="mt-4">
      <v-flex sm12 md4><img src="../assets/img_4.png" /></v-flex>
      <v-flex sm12 md8>
        <h1 class="mt-5">And Yes, with Gomusu, you CAN do one-time payments</h1>
        <p>
          You don’t have to be a regular patron! Support once, without commitment: it still helps.
        </p>
      </v-flex>
    </v-layout>
  </v-container>

  <v-container fluid text-xs-center class="howitworks">
    <h1 class="display-2 font-weight-bold mt-5">How it works</h1>
    <img class="mt-5 fullwidth" src="../assets/youtube_mock.png" />
    <h2 class="display-1 font-weight-bold">1. Install the add-on</h2>
    <v-layout wrap row class="mt-5 img100">
      <v-flex sm12 md4>
        <img src="../assets/payment_methods.png" /><h2 class="display-1 font-weight-bold">2. Set the payment method</h2>
      </v-flex>
      <v-flex sm12 md8>
        <img src="../assets/outta_garage.png" /><h2 class="display-1 font-weight-bold">3. One-click support</h2>
      </v-flex>
    </v-layout>
  </v-container>

  <v-container fluid text-xs-center class="tipsubscribe">
    <h1 class="display-2 font-weight-bold mt-5">Tip those who deserve it</h1>
<!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup" class="mt-5 mb-5">
<form action="https://gomusu.us17.list-manage.com/subscribe/post?u=ea83671015743a0a68746f45e&amp;id=df7a38b83b" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
   <div id="mc_embed_signup_scroll">
    <div class="mc_signup">
    <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="Your email address" required>
   <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
   <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_ea83671015743a0a68746f45e_df7a38b83b" tabindex="-1" value=""></div>
   <div class="clear"><input type="submit" value="I WANT TO SUPPORT" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
   </div>
   </div>
</form>
</div>

  </v-container>
</div>
</template>

<script>
  export default {
    data: () => ({
    })
  }
</script>

<style>
.logo {
  position: absolute;
  text-transform: uppercase;
  font-size: 2rem;
  left: 15%;
  top: 10%;
}
.logo img {
  height: 3rem;
}

.main {
  margin-top: 32vw;
}

#mc_embed_signup form {text-align:center; padding:10px 0 10px 0;}
.mc-field-group { display: inline-block; } /* positions input field horizontally */
#mc_embed_signup input.email {font-family:"Open Sans","Helvetica Neue",Arial,Helvetica,Verdana,sans-serif; font-size: 15px; border: 1px solid #ABB0B2;  -webkit-border-radius: 3px; -moz-border-radius: 3px; border-radius: 3px; color: #343434; background-color: #fff; box-sizing:border-box; height:32px; padding: 0px 0.4em; display: inline-block; margin: 0; width:350px; vertical-align:top;}
#mc_embed_signup label {display:block; font-size:16px; padding-bottom:10px; font-weight:bold;}
#mc_embed_signup .clear {display: inline-block;} /* positions button horizontally in line with input */
#mc_embed_signup .button {font-size: 13px; border: none; -webkit-border-radius: 3px; -moz-border-radius: 3px; border-radius: 3px; letter-spacing: .03em; color: #fff; background-color: #aaa; box-sizing:border-box; height:32px; line-height:32px; padding:0 18px; display: inline-block; margin: 0; transition: all 0.23s ease-in-out 0s;}
#mc_embed_signup .button:hover {background-color:#777; cursor:pointer;}
#mc_embed_signup div#mce-responses {float:left; top:-1.4em; padding:0em .5em 0em .5em; overflow:hidden; width:90%;margin: 0 5%; clear: both;}
#mc_embed_signup div.response {margin:1em 0; padding:1em .5em .5em 0; font-weight:bold; float:left; top:-1.5em; z-index:1; width:80%;}
#mc_embed_signup #mce-error-response {display:none;}
#mc_embed_signup #mce-success-response {color:#529214; display:none;}
#mc_embed_signup label.error {display:block; float:none; width:auto; margin-left:1.05em; text-align:left; padding:.5em 0;}
@media (max-width: 768px) {
    #mc_embed_signup input.email {width:100%; margin-bottom:5px;}
    #mc_embed_signup .clear {display: block; width: 100% }
    #mc_embed_signup .button {width: 100%; margin:0; }
}

#mc_embed_signup{/*background:#fff;*/ clear:left; font:14px Helvetica,Arial,sans-serif; width:100%;}
/* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
    We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
#mc-embedded-subscribe-form input[type=checkbox]{display: inline; width: auto;margin-right: 10px;}
#mergeRow-gdpr {margin-top: 20px;}
#mergeRow-gdpr fieldset label {font-weight: normal;}
#mc-embedded-subscribe-form .mc_fieldset{border:none;min-height: 0px;padding-bottom:0px;}

.mc_signup {
  padding: 1em;
  border-radius: 2.5em;
  background-color: white;
  display: inline-block;
}
#mc_embed_signup .mc_signup .email {
  border-width: 0px;
}
#mc_embed_signup .mc_signup .clear {
  box-shadow: 0 0 0 1em #55bb33;
  border-radius: 2.5em;
  background-color: #55bb33;
}
@media (max-width: 768px) {
  #mc_embed_signup .mc_signup .clear {
    margin-top: 10px;
  }
}
#mc_embed_signup .mc_signup .clear .button {
  background-color: transparent;
}

.personas {
  background-color: white;
  color: #171c34;
}

.personas img {
  width: 100%;
  min-width: 320px;
  max-width: 450px;
}

.personas p {
  color:  #919aa3;
  font-size: 1.3em;
  margin-top: 1em;
  max-width: 80%;
  margin-left: 10%;
}

.howitworks {
  background-color: #f2f2f6;
  color: #131313;
}

.howitworks .fullwidth {
  max-width: 100%;
}

.img100 img {
  max-width: 100%;
}

.tipsubscribe {
  background-color: #5890ff;
  color: white;
}


</style>
