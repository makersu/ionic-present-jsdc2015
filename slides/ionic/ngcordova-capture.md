<div>
<pre><code data-trim="" contenteditable="" class="js vbnet">
$ cordova plugin add org.apache.cordova.media-capture
</code></pre>
</div>

<div>
<pre><code data-trim="" contenteditable="" class="js vbnet">
?$scope.captureImage = function() {
  var options = { limit: 3 };

  $cordovaCapture.captureImage(options).then(function(imageData) {
    // Success! Image data is here
  }, function(err) {
    // An error occurred. Show a message to the user
  });
}
</code></pre>
</div>