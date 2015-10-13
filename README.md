# Vim-Gradle #

The purpose of this project is to maintain missing *Gradle* capabilities in *Vim*. Particularly:

* File extension recognition
* Syntax highlighting
* Folding
* Additional folding for *Groovy* files
* TBD

## Installation ##

### Vim Pathogen Plugin ###

If you are using [Vim Pathogen](https://github.com/tpope/vim-pathogen) plugin, then the installation is simple and straightforward:

```
#!shell
cd ~/.vim/bundle
hg clone https://bitbucket.org/sw-samuraj/vim-gradle
```

### Classic Vim Layout ###

If you prefer the traditional *Vim* layout, you can copy all the directories to your `$VIM_HOME`:

```
#!shell
cp -r syntax ftdetect compiler after ~/.vim
```

### Through the Gradle ###

Your interest in the *Vim-Gradle* plugin probably means that you have *Gradle* already installed. Then you can run either

```
#!shell
gradle installBundle
```

for *Pathogen*-like installation, or

```
#!shell
gradle installVimball
```

for *classic*-like installation.

## Uninstallation ##

### Vim Pathogen Plugin ###

```
#!shell
rm -rf ~/.vim/bundle/vim-gradle
```

### Classic Vim Layout ###

```
#!shell
cd ~/.vim
rm -rf syntax/gradle.vim ftdetect/gradle.vim compiler/gradle.vim after/syntax/groovy.vim
```

### Through the Gradle ###

If you have *Gradle* already installed, then you can uninstall *Vim-Gradle* by

```
#!shell
gradle uninstallBundle
```

for the *Pathogen* bundle, or

```
#!shell
gradle uninstallVimball
```

for the *classic* layout.

## TODO ##

* TBD

## Contribution ##

TBD

## License ##

TBD
