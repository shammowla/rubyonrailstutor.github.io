---
layout: post
title:  "Ruby String"
date:   2014-03-04 11:26:42
language: ruby
tags: free ruby coding resources string
categories: basics
repo: https://github.com/rubyonrailstutor/curriculum
---
<iframe width="640" height="360" src="//www.youtube.com/embed/w2x0VtVlxX8?vq=hd1080" frameborder="0" allowfullscreen></iframe>

<h4><a href="{{ page.repo }}" target="_blank">follow along with the source code</a></h4>

``` ruby 
  # http://ruby-doc.org/core-2.1.1/String.html
  # join a social pair programming class http://www.rubyonrailstutor.com

  name = "john"
  name.reverse
  name
  name.class

  # String Concatenation
  first_name = "john"
  last_name = "davison"
  first + last
  first

  # String Interpolation
  first = "john"
  last = "davison"
  complete_name = "#{first} #{last}"
  complete_name

  # how to remove ALL the '*' from messed_up_name ?
  messed_up_name = "j*o*h*n"
  messed_up_name.sub("*", "")
  messed_up_name.gsub("*", "")
  messed_up_name
  name = messed_up_name.gsub("*", "")

  # empty?, length, [0..1], [-1]
  # zero indexing

  name[0]

  #how to find things ? 
  really_messed_up_name = "johnfubardavison"

  # how to find if 'fubar' exists inside really_messed_up_name ? 
  really_messed_up_name.match("fubar")

  # split

  letters = name.split("")

  letters.each do |letter|
    p letter.next
  end

  letter.join("")
  name = letter.join("")

  # join a social pair programming class http://www.rubyonrailstutor.com
```
