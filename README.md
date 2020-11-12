# Description

Do you love minimal UI? this plugin will switch your theme based on the part of day time. This plugin using these two themes: [Xi-hyper](https://github.com/pacocoursey/Xi-Hyper) by [paco](https://paco.im/) and [Xo-hyper](https://github.com/ayikfour/xo-hyper) by [paswotnya](https://twitter.com/paswotnya)

# Install

Edit ~/.hyper.js and include the plugin name:

```
module.exports = {
    config: {
        plugins: ['hyper-day-night-switch'],
    }
}
```

# Config

```
module.exports = {
    config: {
        dayNightSwitch: {
            sunUp: 6,
            sunDown: 21
        },
    }
}
```

# Themes

These are the themes this plugin will use:

```
xo-hyper
xi-hyper
```

# Ported
This plugin was ported from [johnviolano](https://github.com/johnviolano/hyper-day-night-switch) project named [hyper-day-night-switch](https://github.com/johnviolano/hyper-day-night-switch)