# Contributing

This plugin is designed to make it easier for multiple developers to implement their own features.

## How to contribute

| Contribution      | Details                                                                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Report a bug      | You can [file an issue](https://github.com/dm94/SharedPlugin/issues/new/choose) To report a bug.                                                              |
| Contribute code   | You can contribute your code by fixing a bug or implementing a feature.                                                                                       |
| Help to translate | You can help translate the plugin from .                                                                                                                      |
| Help in discord   | There are many users asking for help on discord. [Coding Channel in the official Discord](https://discord.com/channels/523159099870019584/700042416576659456) |

## Contribute Code

To contribute code you can make Pull requests to this repository for review. To do this you have to clone the repository, create a branch, add your code and test it.

Everyone can implement their functionalities, but the code will be reviewed and features that do not comply with DarkBot's rules will not be accepted.

### Clone the repository

The repository can be easily cloned using

```bash
$ git clone https://github.com/dm94/SharedPlugin.git
```

### Create a branch

[Oficial Github Documentation](https://docs.github.com/articles/creating-and-deleting-branches-within-your-repository)

### Add your code

As a plugin, it has two main dependencies for the code to be executed, those dependencies are [DarkBotAPI](https://github.com/darkbot-reloaded/DarkBotAPI) and [DarkBot](https://github.com/darkbot-reloaded/DarkBot).

That said, I recommend that you have knowledge of how both dependencies work as you need them to make new features and test the plugin's functionality.

One of the main rules when making changes is that the direct use of the DarkBot dependency should be avoided and the correct approach is to use the DarkBotAPI.

### Build the plugin

As I use graddle you can run the task 'copyFile' and it will generate a jar called SharedPlugin.jar.

### How to test the changes

When a pull request is made, I will build a version with the changes so that they can be tested.
Each time a merge is performed, a new version will be deployed and the .jar file will be added.
