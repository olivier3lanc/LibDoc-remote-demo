# Jekyll LibDoc locally as remote theme

This `local`branch is a simple example of a repository that you can **build locally with Jekyll LibDoc as remote theme**.

1. Install Jekyll on your machine following the steps described [here](https://jekyllrb.com/docs/)
2. Add a Gemfile with the following line

  ```ruby
  gem "jekyll-remote-theme"
  ```
  and run `bundle install` to install the plugin

3. Add the following to your site's `_config.yml` to activate the plugin

  ```yml
  plugins:
    - jekyll-remote-theme
  ```
  Note: If you are using a Jekyll version less than 3.5.0, use the `gems` key instead of `plugins`.

4. Add the following to your LibDoc's local config file `_config-local.yml`

  ```yml
  remote_theme: olivier3lanc/Jekyll-LibDoc
  plugins:
    - jekyll-remote-theme
  ```
  
5. Run `jekyll build`
