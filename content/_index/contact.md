+++
fragment = "contact"
#disabled = true
date = "2020-05-15"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Contact us"
subtitle  = "Call 8-701-529-0670 or leave us your message"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://example.com/mailout" #default: formspree.io
email = "ord3r1y@protonmail.ch"
button = "Send Button" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Your Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Your Message *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
