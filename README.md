# shiny-happiness

[![Netlify Status](https://api.netlify.com/api/v1/badges/e04bd82d-4399-401e-a412-1aa99a39c236/deploy-status)](https://app.netlify.com/sites/incredible-youtiao-476a93/deploys)

_redrect

[[redirects]]
  from = "/old-path"
  to = "/new-path"
  status = 301
  force = false
  query = {path = ":path"} #  apply this rule for /old-path?path=example
  conditions = {Language = ["en","es"], Country = ["US"]}

[[redirects]]
  from = "/news"
  to = "/blog"
  
[[redirects]]
  from = "https://somenetlifysite.netlify.app"
  to = "https://mycustomdomain.com"
  status = 301
  force = true



[build.processing.html]
  pretty_urls = true
