FROM ruby:2.7

WORKDIR /app
COPY Gemfile Gemfile.lock ./
RUN bundle install

EXPOSE 4000
CMD ["rails", "s", "-p", "4000"]
