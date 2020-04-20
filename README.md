![JetBrains Plugin CI](https://github.com/leeclemens/gitflowgusto/workflows/JetBrains%20Plugin%20CI/badge.svg)
![IntelliJ Platform Plugin Compatibility](https://github.com/leeclemens/gitflowgusto/workflows/IntelliJ%20Platform%20Plugin%20Compatibility/badge.svg)

# Git Flow Integration for IntelliJ Platforms


An IntelliJ plugin providing a UI layer for git-flow, which in itself is a collection of Git extensions to provide high-level repository operations for Vincent [Driessen's branching model](http://nvie.com/git-model).

![screenshot](https://leeclemens.github.io/gitflowgusto/images/menu.png)


## Getting started

For the best introduction to get started with `git flow`, please read Jeff Kreeftmeijer's blog post:

[http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/)

Or have a look at this [cheat sheet](http://danielkummer.github.io/git-flow-cheatsheet/) by Daniel Kummer:

## Who and why

This plugin was created by [Opher Vishnia](http://www.opherv.com), after I couldn't find any similar implementation.
I saw this [suggestion page](http://youtrack.jetbrains.com/issue/IDEA-65491) on the JetBrains site has more than 220 likes and 80 comments, and decided to take up the gauntlet :)

It was later forked by [Lee Clemens](https://github.com/leeclemens) to add support with future versions of IntelliJ.

Huge shoutout [to Kirill Likhodedov](https://github.com/klikh), who wrote much of the original git4idea plugin, without which this plugin could not exist

## Installation

The plugin is available via the IntelliJ plugin manager. Just search for "Git Flow Integration with Gusto" to get the latest version!

**The plugin requires that you have gitflow installed, specifically the [AVH edition](https://github.com/petervanderdoes/gitflow).
 This is because the [Vanilla Git Flow](https://github.com/nvie/gitflow) hasn't been maintained in years.** See this page [for details](https://github.com/leeclemens/gitflowgusto/blob/develop/GITFLOW_VERSION.md)

## Caveats

While the plugin is operational and contains all basic functions (init/feature/release/hotfix), it may contain bugs. With your help I'll be able to find and zap them all.

## Helping out

This project is under active development.
If you encounter any bug or an issue, I encourage you to add them to the [Issues list](https://github.com/leeclemens/gitflowgusto/issues) on Github.
Feedback and suggestions are also very welcome.

## License

This plugin is under the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).
Copyright 2013-2019, Opher Vishnia.
Copyright 2020, Lee Clemens.
