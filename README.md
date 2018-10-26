### CodeRay 
---
https://github.com/rubychan/coderay
http://coderay.rubychan.de/

```ruby
gem install coderay

require 'coderay'
html = CodeRay.scan("puts 'Helo, world!'", :ruby).div(:line_numbers => :table)

```


```ruby
CodeRay.scan('puts "Hello"').div
CodeRay.scan("5.times do\n puts 'Hello\nend'").div(:line_numbers => :table)
tokens = CodeRay.scan('puts "Hello"')
tokens.statistic
CodeRay.scan('[ "just": "an", "example": 42]', :json).loc
tokens.div(:css => :class)
CodeRay.highlight_file(__FILE__)
CodeRay::Duo[:ruby, :div].encode('puts "Hello"')
```

```
```
