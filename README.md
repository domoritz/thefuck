[![][travis-badge]][travis-link]
![][license-badge]

<div align="center">
  <a href="http://github.com/oh-my-fish/oh-my-fish">
  <img width=90px  src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
  </a>
</div>
<br>


# thefuck

This is a fork from [oh-my-fish/plugin-thefuck](https://github.com/oh-my-fish/plugin-thefuck). 

This plug-in creates the necessary function to be used with [The Fuck][thefuck].
It brings:

* Fast initialization (benchmark: diff is 10ms, median)
* Lazy auto-update (only when The Fuck gets updated)
* Key binding for command line replacement


## Install

After [installing The Fuck][thefuck-install], proceed:

```fish
$ omf install thefuck
```


# Key bindings
1. `Esc-Esc` - `thefuck_command_line`

## Usage

```fish
$ git brch
$ fuck
```


# License

[MIT][mit] © [scorphus][author] et [al][contributors]

[thefuck]:         https://github.com/nvbn/thefuck
[thefuck-install]: https://github.com/nvbn/thefuck/#requirements

[mit]:             http://opensource.org/licenses/MIT
[author]:          https://github.com/scorphus
[contributors]:    https://github.com/oh-my-fish/plugin-thefuck/graphs/contributors
[omf-link]:        https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:   https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
[travis-badge]:    http://img.shields.io/travis/oh-my-fish/plugin-thefuck.svg?style=flat-square
[travis-link]:     https://travis-ci.org/oh-my-fish/plugin-thefuck
