# disable_options plugin for selectize.js

See the [Selectize Plugin Docs](https://github.com/brianreavis/selectize.js/blob/master/docs/plugins.md) for general use instructions.

This plugin disables options in a selectize dropdown based on the option's [data-value] attribute. All you need to do is pass in an array of values for the options you want to disable.

```
  $('select').selectize({
    plugins: {
      'disable_options': {
        disableOptions: myArray
      },
    }
  });
```

# selectize.js

Selectize is an extensible jQuery-based custom &lt;select&gt; UI control. It's useful for tagging, contact lists, country selectors, and so on. It clocks in at around ~7kb (gzipped). The goal is to provide a solid & usable experience with a clean and powerful API.

- [Demos](http://brianreavis.github.io/selectize.js/)
- [Changelog](https://github.com/brianreavis/selectize.js/releases)
- [Examples](examples/)
- [Usage Documentation](docs/usage.md)
- [API Documentation](docs/api.md)
- [Plugin Documentation](docs/plugins.md)
