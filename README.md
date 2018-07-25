# angular-icheck
a icheck directive like jQuery iCheck for angularjs
demo is at index.html

```
<!DOCTYPE html>
<html ng-app="app">
<head lang="en">
    <meta charset="UTF-8">
    <title>Angular-iCheck</title>
    <link rel="stylesheet" href="angular-icheck.css"/>
</head>
<body ng-init="male=true">
<i-check ng-model="male">男</i-check>
{{male}}
<script src="bower_components/angular/angular.js"></script>
<script src="angular-icheck.js"></script>
<script>
    angular.module('app',[
            'angular-icheck'
    ]);
</script>
</body>
</html>
```
