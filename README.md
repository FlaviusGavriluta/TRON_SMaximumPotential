# TRON's maximum potential

## Story

As _Clu_ said in _TRON: Legacy_, _"I took this system to its maximum potential."_
The lesson of the movie is that he was wrong. Or was he? His efforts to create the perfect system are at least honorable.
To follow in his footsteps, `Static Code Analysis` can help us minimize false-positives and improve code quality.

Your task is to configure `Phan` and analyze the code of your previously built MVC micro-framework.

## What are you going to learn?

- what is `Static Code Analysis`
- how to install and use `Phan`

## Tasks

1. Install the static analyzer tool called `Phan` to your MVC micro-framework project using Composer.
    - The command `./vendor/bin/phan --version` is available and prints out the version number of `Phan`.

2. Create a `config.php` in a new directory called `.phan`. Specify the target version, the directories you want to analyze and the plugins to use.
    - `config.php` file exists in `.phan` folder and contains the required settings.

3. Analyze the codebase of your MVC micro-framework with `Phan`.
    - Code is analyzed by executing the `./vendor/bin/phan` command.

4. [OPTIONAL] Improve code quality following the instructions of `Phan`.
    - Code quality is improved based on the suggestions of `Phan`.

## General requirements

None

## Hints

- You can increase your productivity by using `Static Code Analysis` during the development.

## Background materials

- <i class="far fa-book-open"></i> [What Is Static Code Analysis?](https://searchsoftwarequality.techtarget.com/definition/static-analysis-static-code-analysis)
- <i class="far fa-exclamation"></i> [The usage of Phan](https://github.com/phan/phan#usage)
