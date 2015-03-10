---
layout: post
title:  "Welcome to Jekyll!"
date:   2014-08-29 14:34:25
categories: jekyll update
tags: featured
image: https://s3-eu-west-1.amazonaws.com/leadgrand/Coming+Soon+Images/leadgrand-01.jpg?X-Amz-Date=20150310T190712Z&X-Amz-Expires=300&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Signature=3e58d1c6538e930fd2424df838612df0fdee11cc812829afe6729fe54b1b3f66&X-Amz-Credential=ASIAIZQPXWJA36COUJJA/20150310/eu-west-1/s3/aws4_request&X-Amz-SignedHeaders=Host&x-amz-security-token=AQoDYXdzEEwagAKuDGeg3vqhrfWq1%2B9rFu2j1z8dPRqsDlPxSjCtqE0mKz0GSL8YJsPkKvimz3Mh77JbqL60CP1HO/dWUTWQv1a36U%2BCgfehAL8uRBzdftJT2cBNNsscEidZ0LG1JuvneFddNrZ6xdlBoObw77Vgj%2BeAY12uJMaTUQCDgivRnLPUi4KYyij9fkQWOYl/oPDx6bPUKINHATV49FkVwVdDDG0urRAFMceYc2/g3bAeSR/fDYPpQEruGUFdTwcGSDwKSze87KS/kZLm5rX%2BzB6VfylLYH9iFQ3IOOOEnYqg%2BrQUOEGJAviHY7BNKU3GTmYh157oFdxA62WnQ1qiZP/8Rhs2IIWB/acF
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

{% highlight js %}

<footer class="site-footer">
 <a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
  <div class="inner">a
   <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; {{ site.time | date: '%Y' }} &bull; All rights reserved.</section>
   <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
  </div>
</footer>
{% endhighlight %}


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
