IDE-SETTINGS
============

In this repo I track the configurations for different IDE's I use per language.

| IDE | Settings for |
|-----|--------------|
| [vscode](https://code.visualstudio.com/) | python |
| [pycharm](https://www.jetbrains.com/pycharm/) | python |

# Using GitHub Issues as Tasks in IntelliJ

1. Use `Ctrl+Alt+s` to open the settings
1. Search for `tasks`
1. Add a new `GitHub` task-server
1. Insert information about the repository and generate a new authentication token
1. Authenticate in the browser
1. Click Apply and OK, and see tasks on the top-right corner of the IDE
1. Now when you select a task the IDE directly creates a branch for it

# Time Tracking

PyCharm does not support time-tracking for tasks, but the [Darkyen's Time Tracking plugin](https://plugins.jetbrains.com/plugin/9286-darkyen-s-time-tracker) seems to
have all required features available.

# Using Vim controls in IntelliJ

1. From the marketplace install and activate the ideaVim-plugin
1. create an `~/.ideavimrc` file with your settings in it (check the ideavim subfolder for an example)
1. restart the IDE and have fun with Vim


