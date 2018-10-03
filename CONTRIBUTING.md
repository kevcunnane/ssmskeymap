
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

## Testing locally

* Install vsce using `npm install -g vsce`
* Run `vsce package` from the root folder of this project to build a .vsix file
* Install the VSIX file in Azure Data Studio