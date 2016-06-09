# ngstrengthjs
by <a href="http://www.efrenbautista.com">Efren Bautista Jr</a>

A simple angular directive wrapper for Strength.js jquery library from <a href="https://github.com/aarondo/Strength.js.git"> </a>
by <a href="https://github.com/aarondo">aarondo</a>

# How to install
Install using bower:

bower install ngstrengthjs --save<br><br>

Add to your app.js:

ngStrengthjs

# Add to your controller
```html
        $scope.strengthjsOptions = {
                strengthClass: 'strength',
                strengthMeterClass: 'strength_meter',
                strengthButtonClass: 'button_strength',
                strengthButtonText: 'Show Password',
                strengthButtonTextToggle: 'Hide Password'
            };

```

# Add libraries
```html
<script type="text/javascript" src="bower_components/pass-strength/strength.js"></script>
<script type="text/javascript" src="bower_components/ngstrengthjs/dist/ngstrengthjs.js"></script>
```
# Usage
```html

<div ng-model="vm.country" country-select></div>
<div country="{{ vm.country }}" ng-model="vm.state" state-select></div>
```
