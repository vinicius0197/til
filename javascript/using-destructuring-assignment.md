# Using destructuring assignment on function calls

If you pass an object to a function like this:

```javascript
  const obj = { id: 1, name: 'name' };
  myFunction(obj);
```

You can select only the fields you want by using destructuring assignment:

```javascript
  function myFunction({ id }) {
    // do something
  }
```