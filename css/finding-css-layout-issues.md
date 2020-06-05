### Finding CSS layout issues

If you are having some weird CSS layout bugs (like stuff overflowing out of nowhere and causing layout issues), add
the following rule to the base CSS rule on your page:

```
* {
  border: 1px solid #f00 !important;
}
```

This will add red borders to all elements and allow you to easily inspect everything in your page. Really neat hack :)
