source "https://rubygems.org"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Plugins essenciais
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-paginate-v2"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed", "~> 0.12"
end

# Dependências para Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Dependências específicas de plataforma
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Dependências de desenvolvimento
group :development do
  gem "webrick"
end
