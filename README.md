# 🎩 Dantes for Windows Terminal 

## [Windows Terminal](https://github.com/microsoft/terminal)

## Activating theme

Start Windows Terminal and click on the down arrow symbol `˅` from menu bar. And you can see the settings menu. Or you can use `Ctrl + ,` to open Settings directly.

In the `settings.json` settings file for Windows Terminal, find the `schemes` section and paste the content of `dantes.json`.

Once the color scheme has been defined, it's time to enable it. Find the `profiles` section and add a `colorScheme` value to the default profile.

Example:

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Monte-Cristo"
    }
}
```

If the profiles are listed as below:

```jsonc
"profiles": [
    // list of profiles
]
```

Change it to:

```jsonc
"profiles": {
    "defaults": {
      "colorScheme": "monte-cristo"
    },
    "list": [
      // list of profiles
    ]
  },
```

## More info.

You can find more apps on [this website](https://dantestheme.github.io/dantes-website/).  
If you'd like to contribute to this theme, please visit our [Github](https://github.com/dantestheme/dantes-theme). You can also know about more informations too.
