## Ionic UI Components

<div class="col preview demo-frame">
  <iframe src="demos/list/index.html"></iframe>
</div>
<div class="col code">
  <h4>Complex Lists</h4>
  <ul style="margin-left: 70px">
    <li class="default">AngularJS Directive</li>
    <li class="default">Buttons exposed by swiping</li>
    <li class="default">Reorder</li>
    <li class="default">Delete</li>
  </ul>
  <pre>
<code data-trim contenteditable class="xml">
<ion-list>
  <ion-item ng-repeat="item in items" item="item">
    List Item {{ item.id }}
  </ion-item>
</ion-list>
</code>
	</pre>
</div>