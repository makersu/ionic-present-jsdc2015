<!-- <h1>Directives</h1> -->
<h2>Kinds of Directive</h2>
<ul style="margin-left:180px;">
  <li class="default">E - Element name: `<my-directive></my-directive>` </li>
  <li class="default">A - Attribute: `<div my-directive="exp"></div>` </li>
  <li class="default">C - Class: `<div class="my-directive: exp;"></div>` </li>
  <li class="default">Comment: `<!-- directive: my-directive exp -->` </li>
</ul>
<h2>Built-in Directive</h2>
<ul style="margin-left:180px;">
  <li class="default">ng-app (A): `<html ng-app="phonecatApp">`</li>
  <li class="default">ng-controller (A, C): `<body ng-controller="PhoneListCtrl">`</li>
  <li class="default">ng-model (A, C): `<input ng-model="query">`</li>
  <li class="default">ng-click (A, C): `<button ng-click="newTask()">OK</button>`</li>
  <li class="default">ng-repeat (A, C): `<li ng-repeat="phone in phones | filter:query">`</li>
  <li class="default">...</li>
</ul>
<aside class="notes">
element directive, attribute directive, class directive, comment directive...
At a high level, directives are markers on a DOM element (such as an attribute, element name, comment or CSS class) that tell AngularJS's HTML compiler ($compile) to attach a specified behavior to that DOM element (e.g. via event listeners), or even to transform the DOM element and its children.<br>
For AngularJS, "compilation" means attaching directives to the HTML to make it interactive. The reason we use the term "compile" is that the recursive process of attaching directives mirrors the process of compiling source code in compiled programming languages.
</aside>