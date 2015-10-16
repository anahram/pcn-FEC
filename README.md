# pcn-FEC
Front End Cummunity
공부합시다 윤희권...

사용법은 윤희권 에게

<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
<div ng-app="myApp">
    <div ng-controller="Sda">
        {{ sample}}
    </div>
</div>
<script>
var myApp = angular.module('myApp', []);

myApp.controller('Sda', ['$scope', function ($scope) {

    $scope.sample = 'Hello, Angular fanatic.';

}]);
</script>
