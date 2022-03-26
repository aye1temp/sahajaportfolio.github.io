# Welcome to Jekyll!
#
# This config file is meant for settings that affect your whole blog, values
# which you are expected to set up once and rarely edit after that. If you find
# yourself editing this file very often, consider using Jekyll's data files
# feature for the data you need to update frequently.
#
# For technical reasons, this file is *NOT* reloaded automatically when you use
# 'bundle exec jekyll serve'. If you change this file, please restart the server process.

# Site settings
# These are used to personalize your new site. If you look in the HTML files,
# you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
# You can create any custom variable you would like, and they will be accessible
# in the sites via {{ site.myvariable }}.
title: AyePages™ 
email:
description: >- # this means to ignore newlines until "baseurl:"
  This is  an AyePages™ site meant for academic purposes
twitter_username: username
github_username: username
minimal_mistakes_skin: dirt
search: true

# Build settings
markdown: kramdown
remote_theme: projectvikram/projecttheme
# Outputting
permalink: /:categories/:title/
paginate: 5 # amount of posts to show
paginate_path: /page:num/
timezone: # https://en.wikipedia.org/wiki/List_of_tz_database_time_zones

include:
  - _pages

# Exclude from processing.
# The following items will not be processed, by default. Create a custom list
# to override the default setting.
# exclude:
#   - Gemfile
#   - Gemfile.lock
#   - node_modules
#   - vendor/bundle/
#   - vendor/cache/
#   - vendor/gems/
#   - vendor/ruby/

# Plugins (previously gems:)
plugins:
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-gist
  - jekyll-feed
  - jemoji
  - jekyll-include-cache

author:
  name   : "Sahaja Katta"
  avatar : "/assets/images/ayetutor.png"
  bio    : "AyeAI is a cognitive edutech company. We make technology democratic."
  links:
    - label: "Twitter"
      icon: "fab fa-fw fa-twitter-square"
      url: "https://twitter.com/"
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/"
    - label: "Instagram"
      icon: "fab fa-fw fa-instagram"
      url: "https://instagram.com/"
    - label: "Facebook"
      icon: "fab fa-fw fa-facebook"
      url: "https://www.facebook.com/"
    - label: "LinkedIn"
      icon: "fab fa-fw fa-linkedin"
      url: "https://www.linkedin.com/"

footer:
  links:
    - label: "Advisors"
      icon: "fas fa-fw fa-award"
      url: "/advisors/"
    - label: "Team"
      icon: "fas fa-fw fa-users-cog"
      url: "/team/"
    - label: "Partners"
      icon: "fas fa-fw fa-handshake"
      url: "/partners/"
    - label: "License"
      icon: "fas fa-fw fa-file-contract"
      url: "/license/"
    - label: "Privacy Policy"
      icon: "fas fa-fw fa-mask"
      url: "/privacy/"
    - label: "Term & Conditions"
      icon: "fas fa-fw fa-balance-scale-right"
      url: "/terms/"

defaults:
  # _pages
  - scope:
      path: "_pages"
      type: pages
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
  # _posts
  - scope:
      path: "_posts"
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

category_archive:
  type: liquid
  path: /categories/
tag_archive:
  type: liquid
  path: /tags/
