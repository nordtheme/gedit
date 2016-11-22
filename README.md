<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-gedit/develop/src/assets/nord-gedit-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/nord-gedit/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-gedit.svg"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-blue.svg"/></a> <img src="https://static.gnome.org/wiki.gnome.org/gnome/css/favicon.png" width=16 height=16/> <a href="https://wiki.gnome.org/Projects/GtkSourceView"><img src="https://img.shields.io/badge/GtkSourceView-v3.22.1-blue.svg"/></a></p>

<p align="center">A arctic, north-bluish clean and elegant <a href="https://wiki.gnome.org/Apps/Gedit">gedit</a> color scheme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-top.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Getting started
### Installation
#### Manual
Copy the [`nord.xml`](https://github.com/arcticicestudio/nord-gedit/tree/develop/src/xml/nord.xml) file to the color schemes directory according to the desired installation type.

Local: `~/.local/share/gedit/styles`
Global: `/usr/share/gtksourceview-3.0/styles`

#### Import
[Download](https://github.com/arcticicestudio/nord-gedit/releases/latest) the latest [`nord.xml`](https://github.com/arcticicestudio/nord-gedit/blob/develop/src/xml/nord.xml) file and import it:
  1. Open the preferences
  2. Switch to the *Font & Colors* tab
  3. Click on the *+* labeled button on the left bottom
  4. Import the downloaded `nord.xml` file

#### Install Script
The included `install.sh` shell script can be used for an automated installation.  
If no option is specified, the default installion type is local and the scheme file is `src/xml/nord.xml`.

A list of available options can be shown with the `--help` option.
![][scrot-readme-install-script]

**Note**: The global installation requires root privileges via `sudo`!

### Activation
  1. Open the preferences
  2. Switch to the *Font & Colors* tab
  3. Select `Nord` from the *Color Scheme* list

## Features
<p align="center"><strong>Non-obtrusive bracket matching- and search marker</strong><br/><img src="https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-feature-bracketmarker.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-feature-findandreplace.png"/></p>

<p align="center"><strong>Colors of selected code can still be easily recognized</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrcast-feature-selection.gif"/></p>

<p align="center"><strong>Clear visual distinction for selections of search interactions</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrcast-feature-findandreplace.gif"/></p>

## Languages
This theme provides optimized styles to achieve a consistent and uniform coloring across languages.  
Detailed descriptions for supported languages can be found in the [project wiki](https://github.com/arcticicestudio/nord-gedit/wiki).

### C
![][scrot-lang-c]

### CSS
![][scrot-lang-css]

### diff
![][scrot-lang-diff]

### <img src="https://www.w3.org/html/logo/downloads/HTML5_Badge.svg" width=16 height=16/> [HTML](https://html.spec.whatwg.org/multipage/)
![][scrot-lang-html]

### <img src="https://javascript.com/images/favicon.ico" width=16 height=16/> [JavaScript](https://javascript.com/)
![][scrot-lang-javascript]

### <img src="http://www.json.org/favicon.gif" width=16 height=16/> [JSON](http://www.json.org)
![][scrot-lang-json]

### <img src="https://facebook.github.io/react/favicon.ico" width=16 height=16/> [React JSX](https://facebook.github.io/react)
![][scrot-lang-jsx]

### <img src="http://php.net/images/logo.php" width=16 height=16/> [PHP](http://php.net)
![][scrot-lang-php]

### <img src="https://www.python.org/static/favicon.ico" width=16 height=16/> [Python](https://python.org)
![][scrot-lang-python]

### <img src="https://www.ruby-lang.org/favicon.ico" width=16 height=16/> [Ruby](https://ruby-lang.org)
![][scrot-lang-ruby]

### Shell
![][scrot-lang-shell]

## Development
[![](https://img.shields.io/badge/Changelog-0.1.0-blue.svg)](https://github.com/arcticicestudio/nord-gedit/blob/v0.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-blue.svg)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-blue.svg)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-gedit/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center"> <img src="http://arcticicestudio.com/favicon.ico" width=16 height=16/> Copyright &copy; 2016 Arctic Ice Studio</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg"/></a></p>

[scrot-lang-c]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-c.png
[scrot-lang-css]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-css.png
[scrot-lang-diff]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-diff.png
[scrot-lang-html]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-html.png
[scrot-lang-javascript]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-top.png
[scrot-lang-json]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-json.png
[scrot-lang-jsx]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-jsx.png
[scrot-lang-php]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-php.png
[scrot-lang-python]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-python.png
[scrot-lang-ruby]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-ruby.png
[scrot-lang-shell]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-lang-shell.png
[scrot-readme-install-script]: https://raw.githubusercontent.com/arcticicestudio/nord-gedit/develop/src/assets/scrot-readme-install-script.png
