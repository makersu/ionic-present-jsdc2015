<div class="col preview demo-frame">
  <iframe src="demos/popover/index.html"></iframe>
</div>
<div class="col code">
  <h2>Popover</h2>
  <ul style="margin-left: 70px">
    <li>AngularJS Service</li>
    <li>Inline or external template</li>
  </ul>
<pre><code data-trim="" contenteditable="" class="js vbnet">
$ionicPopover.fromTemplateUrl('popover.html',
  function(popover) {
    $scope.popover = popover;
  }
);
</code></pre>
<pre><code data-trim="" contenteditable="" class="js vbnet">
<ion-popover-view>
  <ion-header-bar>
    <h1 class="title">My Popover Title</h1>
  </ion-header-bar>
  <ion-content class="padding">
    Hello!
  </ion-content>
</ion-popover-view>
</code></pre>
</div>
