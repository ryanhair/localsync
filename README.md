# localsync
Uses bluetooth 4.0 to communicate between local devices
## simple use
```JavaScript
var ref = new Localsync("someidentifier");
ref.send('addUser', { name: "John Doe", age: 22 });
ref.on('addUser', function(user) {
  console.log(user.name + ' added!');
});
```
