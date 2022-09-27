FROM jekyll/jekyll:4.1.0 as blog-base
MAINTAINER Jaroslav Bezdek

COPY Gemfile .
# COPY Gemfile.lock .

RUN bundle install

WORKDIR /usr/src/app

RUN chown -R nobody /usr/src/app/
RUN usermod --home /tmp nobody

USER nobody

CMD ["bundle", "exec", "jekyll", "serve", "--livereload", "--host", "0.0.0.0"]
