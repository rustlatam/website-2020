Website of the Rust Latam 2020

-----
# Theme forked from: [Grayscale](https://github.com/jeromelachaud/grayscale-theme/)

## Original source: [Jekyll Themes](http://themes.jekyllrc.org/grayscale/)

## Run with Docker

- Check out the repo
- docker run --rm --volume=$(pwd):/srv/jekyll -p 35729:35729 -p 4000:4000 -it jekyll/jekyll jekyll serve

or with Docker Compose

- docker-compose up

## Run locally without docker

As per the [jekyll docs](https://jekyllrb.com/)

- `gem install bundler`
- `bundle install --path vendor/bundle`
- `bundle exec jekyll serve`
