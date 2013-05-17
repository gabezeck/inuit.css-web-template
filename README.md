# Inuit.lesscss

This is a LESS port of Harry Robert's [inuit.css-web-template](https://github.com/csswizardry/inuit.css-web-template).

This fork is not endorsed by [@csswizardry](https://github.com/csswizardry/).
We like inuit.css and we use LESS.

## Installation

This is the LESS port of inuit.css web template; the wrapper for the
[LESS port of inuit.css](https://github.com/peterwilsoncc/inuit.css) framework.

This template is a barebones and unopinionated directory structure which simply
allows you to include the inuit.css core library in your builds as an updatable
Git submodule.

To quickly install inuit.css, run the following commands:

    $ git clone --recursive git@github.com:nicoespeon/inuit.css-web-template.git your-project-folder
    $ cd your-project-folder
    $ ./go

What we are doing here is cloning an instance of the LESS inuit.css-web-template and
its submodules (that’s what the `--recursive` does) into a directory which you
specify. Next we `cd` into that directory and run [our `go` script](https://github.com/nicoespeon/inuit.css-web-template/blob/master/go).
This script (courtesy of [Nick Payne](http://twitter.com/makeusabrew)) simply
removes the web template’s Git instance and replaces it with a fresh one for
your project, whilst also maintaining your inuit.css submodule.

For a more detailed overview on what the LESS port of inuit.css is, and how to install
 and use it, please refer to the documentation in the README in
[the LESS inuit.css repository](https://github.com/peterwilsoncc/inuit.css).

## Differences

LESS and SASS are different languages, some features of the original
can not be ported exactly. Some differences are:

* you have to import the defaults of the core framework before your variables
  in the setup (`style.less`) as there is no such thing as `!default` in LESS

## License

LESS adaption copyright 2013 Peter Wilson & Nicolas Carlo

Original work copyright 2013 Harry Roberts

Licensed under the Apache License, Version 2.0.

---

![inuit.css](http://inuitcss.com/img/content/logo.png)

# inuit.css web template

This is the inuit.css web template; the wrapper for the popular
[inuit.css](https://github.com/csswizardry/inuit.css) framework.

This template is a barebones and unopinionated directory structure which simply
allows you to include the inuit.css core library in your builds as an updatable
Git submodule.

To quickly install inuit.css, run the following commands:

    $ git clone --recursive git@github.com:csswizardry/inuit.css-web-template.git your-project-folder
    $ cd your-project-folder
    $ ./go

What we are doing here is cloning an instance of the inuit.css-web-template and
its submodules (that’s what the `--recursive` does) into a directory which you
specify. Next we `cd` into that directory and run [our `go` script](https://github.com/csswizardry/inuit.css-web-template/blob/master/go).
This script (courtesy of [Nick Payne](http://twitter.com/makeusabrew)) simply
removes the web template’s Git instance and replaces it with a fresh one for
your project, whilst also maintaining your inuit.css submodule.

For a more detailed overview on what inuit.css is, and how to install and use
it, please refer to the documentation in the README in
[the main inuit.css repository](https://github.com/csswizardry/inuit.css).
