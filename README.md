# angularjs1-5-inline-template
AngularJS 1.5 Inline Template

Based on 'Inline Template' at https://www.youtube.com/watch?v=OdRuVyi7NuI&index=35&list=PL6n9fhu94yhWKHkcL7RJmmXyxkuFB3KSl

#Inline Template

```javascript
$routeProvider
            .when("/home", {
                template: "<h2>I am an inline template</h2>",
                controller: "homeCtrl",
                controllerAs: "ctrl"
            })
```

See script.js, index.html and styles.css how to implement this.
