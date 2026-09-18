source "https://rubygems.org"

# NOTE ON LOCAL PREVIEW: this machine's system Ruby (2.6.10) cannot
# compile ANY native-extension gem right now — `bundle install` fails
# identically on eventmachine, ffi, etc. with "the compiler failed to
# generate an executable file", regardless of which gem or Jekyll
# version is pinned. This is a well-known macOS system-Ruby toolchain
# issue, not something fixable from the Gemfile. To get local
# `jekyll serve`/`build` working, install a modern Ruby via Homebrew or
# rbenv (`brew install ruby`, then re-open the shell so `ruby -v` shows
# the Homebrew one, not >/usr/bin/ruby<) and re-run `bundle install`.
# Until then, GitHub Pages itself will still build this site fine on
# push (it uses its own build environment, unrelated to this machine).
gem "jekyll", "~> 4.3"

gem "jekyll-sitemap"
gem "jekyll-seo-tag"

# Needed for `jekyll serve` on Ruby >= 3.0 (webrick was removed from stdlib).
gem "webrick", "~> 1.8"
