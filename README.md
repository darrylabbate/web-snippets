## About

This is a (growing) collection of CSS snippets mainly for my own personal reference.

All CSS is written in Sass (original indented syntax) and compiled to CSS and SCSS using the [Sass](https://github.com/sass/dart-sass) executable (installed via [Homebrew](https://brew.sh)).

HTML is written in Slim format and compiled to HTML with the [Slim gem](https://github.com/slim-template/slim).

Screenshots are taken in Safari. All CSS is typically tested in Chrome.

## Creating new snippets with `new`

```bash
$ ./new <snippet-name>
```

The shell script creates a new subdirectory and copies template files from `.templates` to the newly created subdirectory. It serves as a small bootstrap for creating snippets a little more quickly.

You may need to run `chmod +x new` in order for the script to be executable.
