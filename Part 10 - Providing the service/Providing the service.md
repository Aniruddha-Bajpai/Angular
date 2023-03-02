# AngularJS Services

In AngularJS, a service is a function, or object, that is available for, and limited to, your AngularJS application.

## Why use Services?

AngularJS constantly supervises your application, and for it to handle changes and events properly, AngularJS prefers that you use the $location service instead of the window.location object.

    $http service
      makes a request to the server and let's your application handle the response
    $timeout
      angularJS version of windows.setTimeout
    #interval
      angularJS version of windows.setInterval
