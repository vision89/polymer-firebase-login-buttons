# polymer-firebase-login-buttons

An element that includes a styled button and allows logging in through google, firebase, and twitter


## Install

		bower install polymer-firebase-login-buttons --save

## Examples

		<div>
        
        <firebase-google-login-button  firebase-url="fb-google-login-app.firebaseIO.com" user="{{user}}"
          on-google-logged-in="googleLoggedIn" on-google-logged-out="googleLoggedOut"></firebase-google-login-button>

      </div>

      <br />

      <div>
        
        <firebase-facebook-login-button firebase-url="fb-fbook-login-app.firebaseIO.com" user="{{user}}"
          on-facebook-logged-in="facebookLoggedIn" on-facebook-logged-out="facebookLoggedOut"></firebase-facebook-login-button>

      </div>

      <br />

      <div>
        
        <firebase-twitter-login-button firebase-url="fb-twitter-login-app.firebaseIO.com" user="{{user}}"
          on-facebook-logged-in="twitterLoggedIn" on-facebook-logged-out="twitterLoggedOut"></firebase-twitter-login-button>

      </div>