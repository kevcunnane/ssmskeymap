
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

You can read more about how to contribute keybindings in extensions in the [official documentation](http://code.visualstudio.com/docs/extensionAPI/extension-points#_contributeskeybindings) for VS Code. The same process works for SQL Operations Studio.

## Testing locally
If you're doing something complicated you might want to test locally. Here's how.

**Prerequisites**
- Have VSCode installed on your machine, and install the `SQL Operations Studio Debug` from the VSCode marketplace
- Have `sqlops` on your PATH. Open SQL Operations Studio and run the `Install sqlops command in PATH` command to do this
** Testing inside SQL Ops Studio
- Clone the repository to your machine
- Using VSCode, open the folder
- Add your own shortcut as explained above
- Hit F5 to debug it inside SQL Operations Studio. This will open SQL Operations Studio with your version of the extension running. 
- Try out the new shortcut in SQL Operations Studio!

