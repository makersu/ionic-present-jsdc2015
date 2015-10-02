<h1>ngcordova $cordovaCapture</h1>
<!-- <h3>This plugin allows you to record sound, video and images through the native capabilities of the device.</h3> -->
<!-- This plugin allows you to record sound, video and images through the native capabilities of the device. -->

Get the Source File

<pre><code data-trim="" contenteditable="" class="js vbnet">
$ bower install ngCordova
</code></pre>

Inject as an Angular dependency
<pre><code data-trim="" contenteditable="" class="js vbnet">
angular.module('myApp', ['ngCordova'])
</code></pre>

Add the plugin to your project using the Cordova CLI
<pre><code data-trim="" contenteditable="" class="js vbnet">
$ cordova plugin add org.apache.cordova.media-capture
</code></pre>

Use $cordovaCapture service
<pre><code data-trim="" contenteditable="" class="js vbnet">
$scope.captureImage = function() {
  var options = { limit: 3 };

  $cordovaCapture.captureImage(options).then(function(imageData) {
    // Success! Image data is here
  }, function(err) {
    // An error occurred. Show a message to the user
  });
}
</code></pre>