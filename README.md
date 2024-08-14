[![PhingVersion](https://img.shields.io/badge/Phing-2.x-orange.svg?label=Phing%20Verison)]()
# Joomla Phing Tasks for PHP Storm
Massive change of Joomla project information in all files: in XML manifestos and PHP Doc blocks.

# Task list
## Info
Show Phing and project info in console
## Prepare release
Change version to release version and set current creation date. Update package name, copyrights, author name, email, link.
### Copyrights
If your project has been around for a long time, then usually the start date and the current date are indicated in the copyrights. The parameter `projectdatestart` is intended for this purpose.
## Package release
Package release version to ZIP. Zipped extension will placed into `.packages` folder
## Reset since
Change since variables to developer version
## Reset to dev
Change version variables to developer version `__DEPLOY_VERSION__`
## Package dev
Package developer version.

# Demo video
[![](https://img.youtube.com/vi/z64SPHc6TCA/0.jpg)](https://www.youtube.com/watch?v=z64SPHc6TCA)

# How to use
Copy this files to your PHP Storm project. Right-click on the `.phing/project.xml` and select `Add as a Phing Build file`. Select task you need in Phing Build window. 

# Links
- [PHP Storm PHing docs](https://www.jetbrains.com/help/phpstorm/using-phing.html)
- [Igor Berdichevskiy](https://github.com/Septdir) - first author