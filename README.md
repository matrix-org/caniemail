# Can it matrix

[can it matrix](https://matrix-org.github.io/canitmatrix/) provides a quick and easy way to discover who supports what feature in the matrix ecosystem.

This runs on [Jekyll](https://jekyllrb.com/docs/) as [GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages) site with a home made theme. The site uses [Sass](https://sass-lang.com/) for CSS compilation.

## Installation

1. **Clone the repository**.

```sh
git clone https://github.com/matrix-org/canitmatrix.git
```

See [Cloning a repository](https://help.github.com/en/articles/cloning-a-repository) on GitHub documentation. If you're not familiar with Git or GitHub, I strongly encourage you to try [GitHub's desktop app](https://desktop.github.com/) on macOS, Windows or Linux.

2. **Install Jekyll**.

```sh
gem install bundler jekyll
```

See [Jekyll Installation Guide](https://jekyllrb.com/docs/installation/).

3. **Run Jekyll**.

```sh
bundle exec jekyll serve
```

You can turn on [incremental regeneration](https://jekyllrb.com/docs/configuration/incremental-regeneration/) with the `--incremental` flag.

```sh
bundle exec jekyll serve --incremental
```

The _embed_ version of the site ([embed.caniemail.com](https://embed.caniemail.com)) is built by specifiying the config file to use.

```sh
bundle exec jekyll serve --config _config.embed.yml
```

4. **Go to [http://localhost:4000](http://localhost:4000)**.



## Usage

### Folders structure

Here is a quick overview of the project's folders structure:

* Data:

    - `_data`: Data files used throughout the site. This is mainly for settings and labels.
    - `_features`: Data for every features support.
    - `_posts`: Data for the latest news.
    - `tests`: HTML tests files to test features.

* Layout:

    - `_includes`: Files included in other theme files.
    - `_layouts`: The main layouts of the site.
    - `_sass`: Sass files. All files will be compiled into one in the `assets/css/` folder.
    - `assets`: CSS, images, and JavaScript files.


## Credits

This is a fork of the amazing [can I email](https://www.caniemail.com) project by [HTeuMeuLeu](https://github.com/hteumeuleu), adapted for the matrix ecosystem.
## Licence

[MIT Licence](https://github.com/hteumeuleu/caniemail/blob/master/LICENSE)