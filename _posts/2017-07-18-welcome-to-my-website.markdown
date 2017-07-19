---
layout: post
title:  "Welcome to my Website!"
date:   2017-07-18 08:20:00 -0400
categories: jekyll update
---
This website will be used to track my personal projects as well as serve as a centralized repository for my many faces on the internet. 
In the spirit of EECS 381, I'd like to start by using the Meyers singleton to make sure the initialization of this site won't let any copycats follow suit.

{% highlight c++ %}
class Website
{
public:
    static Website& get_instance() 
    {
        static Website site;
        return site;
    }

private:
    Website();
    ~Website();
}
#=> Creates a single website.
{% endhighlight %}

I hope you enjoy any posts to come! Feel free to explore the rest of the site using the links on the right.
