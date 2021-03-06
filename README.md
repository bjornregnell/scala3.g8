# scala3.g8
A simple project template for [Scala 3](https://docs.scala-lang.org/scala3/new-in-scala3.html). You only need to have [JDK](https://adoptopenjdk.net/) and [sbt](https://www.scala-sbt.org) installed. 

## Usage

### In terminal...
...just type:
```
sbt new bjornregnell/scala3.g8
```
When prompted type a project name. When "Template applied", navigate to the new folder, start `sbt` and `run`

### In [VS Code](https://code.visualstudio.com/download) with [Scala (Metals)](https://scalameta.org/metals/docs/editors/vscode.html#installation) do this ...

* Click the curly *m* icon in the left bar
* Click "New Scala Project" under "BUILD COMMANDS"
* Scroll down **almost to the bottom** and select "**Custom** *Enter template manually*"
* Type `bjornregnell/scala3.g8` and confirm with Enter, "OK", "Yes", etc. 

### Settings

The compiler settings in the file [`build.sbt`](https://github.com/bjornregnell/scala3.g8/blob/master/src/main/g8/build.sbt) includes the `-source future` setting, which means that future Scala syntax is enabled and old syntax gives errors. 

If you want the compiler to allow old Scala syntax and help with migration use `-source future-migration` instead, see further information here: https://dotty.epfl.ch/docs/usage/language-versions.html 

## Alternatives

You can also use the bigger [official Scala template](https://github.com/scala/scala3.g8) by typing this in terminal:
```
sbt new scala/scala3.g8
```
This template includes more stuff, such as  library dependencies for testing, etc.

## Credits

This template is based on [Gitter8](http://www.foundweekends.org/giter8/index.html) and the [official Scala template](https://github.com/scala/scala3.g8).