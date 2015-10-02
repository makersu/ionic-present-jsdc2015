## Cordova Plugin Conventional Structure
<pre><code data-trim="" contenteditable="" class="js vbnet">
- Plugin top-level folder
     - plugin.xml
     - src/
        - android/
           - Java source code/
        - ios/
           - Objective-C or Swift source code/
     - www/
        - JavaScript interface/
</code></pre>

### Cordova JavaScript Interface
<pre><code data-trim="" contenteditable="" class="js vbnet">
cordova.exec(successCallback, failureCallback, service, action, [args]);
</code></pre>
<aside class="notes">
<p style="font-size:16px">This call invokes the action method on the service class on the native side, passing the arguments in the optional args array.</p>
</aside>
