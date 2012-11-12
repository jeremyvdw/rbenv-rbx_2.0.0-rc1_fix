# rbenv-rbx_2.0.0-rc1_fix

This is a plugin for [rbenv](https://github.com/sstephenson/rbenv)
that fixes up your shims and sets your RBENV_COMMAND_PATH properly for rbx-2.0.0-rc1 in 1.9 mode.

This plugin is based on Collin Schaafsma's fix for [rbx-2.0.0-dev](https://github.com/collinschaafsma/rbenv-rbx_2.0.0-dev_fix)

## Installation

To install rbenv-rbx_2.0.0-rc1_fix, clone this repository into your
`~/.rbenv/plugins` directory. (You'll need a recent version of rbenv
that supports plugin bundles.)

    $ mkdir -p ~/.rbenv/plugins
    $ cd ~/.rbenv/plugins
    $ git clone https://github.com/jeremyvdw/rbenv-rbx_2.0.0-rc1_fix.git


## Install gems

Be sure to install gems using -X19 options (or gems will be installed under 18 mode)

    $ gem -X19 install bundler

## License

&copy; 2012 Jeremy Van de Wyngaert. Released under the MIT license. See
`LICENSE` for details.
