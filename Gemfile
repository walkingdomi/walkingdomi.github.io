source "https://rubygems.org"

# 깃허브 페이지 공식 지원 버전으로 설정합니다.
gem "github-pages", group: :jekyll_plugins

# Mr. Green 테마 작동에 꼭 필요한 플러그인들입니다.
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
end

# Windows 환경 사용자를 위한 설정입니다.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# 로컬 테스트를 위한 서버 설정입니다.
gem "webrick", "~> 1.7"
