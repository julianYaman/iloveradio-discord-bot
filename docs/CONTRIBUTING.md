# Contributing

If you are interested into contributing to this project, feel free to fork this repository and to submit a pull request with
the changes you made. In future, a special code style will be enforced in all JavaScript files.

**The main recommendation is to use the *standard* code style.**

## Checklist and Contributing guidelines

1. Fork & `git clone` the repository
2. Make sure you are on the **master** branch.
3. Before doing any development, run `npm install`.
4. *Optionally, you can create a development branch for your changes.*
The name should contain the type of change you are doing (e.g. `update-xyz-command`). *You don't have to do this.*
5. Code what you want. (Read **What you need to consider when you code**)
6. Try out your changes and new features with `npm run dev` (nodemon should be installed before using this command).
7. [Submit a pull request.](https://github.com/julianYaman/tune/pull/new/master)

When you submit a pull request, please follow the template.

## What you need to consider when you code:

In the root directory, you need to create a file called `config.js`, otherwise the bot won't start.

The template for this file can be found in `example.config.js`.