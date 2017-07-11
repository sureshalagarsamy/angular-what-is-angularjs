# What is AngularJS?

"AngularJS is a JavaScript framework which simplifies binding JavaScript objects with HTML UI elements."

The javascript class is attached to a HTML parent div tag using ```ng-controller``` directive and the properties are binded directly to the text box using ```ng-model``` declarative.

So now whatever you type in the textbox updates the ```Customer``` object and when the “Customer” object gets updated it also updates the UI.

```javascript
<div ng-controller="Customer">
	<input type=text id="txtCustomerName"  ng-model="CustomerName"/>
</div>
```

In short if you now analyze the above code visually you end up with something as shown in the below figure.

![image](https://user-images.githubusercontent.com/6780840/28066241-cd778500-6659-11e7-9ea0-8a4bc394805c.png)

