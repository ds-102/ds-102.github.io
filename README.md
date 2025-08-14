# Data 102 Fall Website

## Installation

### Install Ruby and Bundler

**The berkeley-class-site template requires Ruby 3.3.7 or higher and bundler >= 2.6**
Install Ruby before continuing. You can check your Ruby version by running:

```bash
ruby --version
bundle --version
```

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

## Clone the repository and install dependencies

Clone with SSH

```bash
git clone git@github.com:ds-102/ds-102.github.io.git
bundle install
```

## Usage

To run the site locally, run:

```bash
cd ds-102.github.io
bundle exec jekyll serve
```

Note that if you alter `_config.yml`, you will need to rerun the above command to see the changes reflected.

## Deployment

Via [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## License

[MIT](LICENSE)
