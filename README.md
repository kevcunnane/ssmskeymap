# SSMS Keymap for Azure Data Studio

This extension ports the most popular SSMS keyboard shortcuts to Azure Data Studio. After installing the extension and restarting VS Code your favorite keyboard shortcuts from SSMS are now available. 

## What keyboard shortcuts are included?

You can see all the keyboard shortcuts in the [package.json file](https://github.com/kevcunnane/ssmskeymap/blob/master/package.json#L23). 

## Why don't all SSMS commands work? 

Azure Data Studio has not implemented all features. Head on over to [GitHub issue](https://github.com/Microsoft/azuredatastudio/issues) and let the Azure Data Studio team know what you'd like to see. 

## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR. 

1. Head over to our [GitHub repository](https://github.com/kevcunnane/ssmskeymap). 
2. Open the [`package.json` file](https://github.com/kevcunnane/ssmskeymap/blob/master/package.json). 
4. Open a pull request. 

```json
{
    "mac": "<keyboard shortcut for mac>",
    "linux": "<keyboard shortcut for linux",
    "win": "<keyboard shortcut for windows",
    "key": "<default keyboard shortcut>",
    "command": "<name of the command in VS Code"
}
```

You can read more about how to contribute keybindings in extensions in the [official documentation](http://code.visualstudio.com/docs/extensionAPI/extension-points#_contributeskeybindings) for VS Code. The same process works for Azure Data Studio.



## License
[MIT](license.txt)
