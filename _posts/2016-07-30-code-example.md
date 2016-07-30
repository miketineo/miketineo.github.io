---
layout: post
title:  "This is a code example"
date:   2016-07-30 12:23:17 +0000
categories: hacking
---


## This is a code example

This is a [link](http://miketineo.com)

and this is a funny gif

![Atl Text](http://i.giphy.com/l3E6MlCQSxa7HZY0E.gif)

```
class FooBar
  
  SOMETHING = "shall not change" unless defined? SOMETHING

  def foo
    return unless bar?

    p "you are in foo"
    SOMETHING.gsub(/\snot\s/, \\1)
  end

  def bar?
    self.respond_to?(:foo)
  end
end
```

### Subtitle

And more stuff
