# TIME TO TAKE CHARGE

## The `ng-model` directive

With the ng-model directive, we can bind the value of HTML input field to a variable created in angularJS. Here, binding is in both ways. If the user changes the value of the input field, the angularJS property will also change its value.

Suppose, if you have used a 'inputval' variable and applied the ng-model directive on the input field. Then the value of input field would be the value stored in 'inputval' variable. But now if you change the value of input field to something else, the same changes would reflect in the variable declared in angular

## SOME FEATURES OF THE MODEL DIRECTIVE

1. It provide type validation for application data (number, e-mail, required)
2. It also provide status for applicatoin data (dirty, valid, touched)
3. It also provide CSS classes for HTML elements, depending upon their status

   Following directive of ng-model add/remove classes

   1. ng-empty
   2. ng-not-empty
   3. ng-touched
   4. ng-untouched
   5. ng-valid
   6. ng-invalid
   7. ng-dirty
   8. ng-pending
   9. ng-pristine
