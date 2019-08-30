---
layout: post
title:  "Welcome to xpchen's Blog"
date:   2019-08-30 21:04
categories: firstblog
permalink: /firstblog
---

This is my first blog of this website. Thanks to Jekyll, I can rebuild the site in many different ways easily. A theme named EasyBook is also used which offers me more choices to improve it.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

<!--more-->

## Jekyll Basic Functions ##

GitHub Flavored Markdown is supported.

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

And $$\mathcal{ Mathematics }$$ is supported!

Use `$$` to wrap your formulas. For example, `$$ e^{i\pi} + 1 = 0 $$` displays $$  e^{i\pi} + 1 = 0  $$

Multi-line forumlas are supported too.

$$
\begin{aligned}
& J(w, b) = \frac{1}{m} \sum_{i=1}^{m}L(\hat{y}^{(i)}, y^{(i)})
+ \frac{\lambda}{2m} \sum_{l=1}^{L}{||w||}^2_F\\\\
& {||w||}^2_F = \sum_{i = 1}^{n[l]}\sum_{j = 1}^{n[l-1]}(w_{ij})^2
\end{aligned}
$$

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

## EasyBook ##

I'm using [EasyBook][github-easybook] the template from [laobubu.net](http://laobubu.net). 

### Advanced Functions ###

Some features are supported now:

* **Pagination** is enabled.
* **Disqus** or **多说** is ready.
* **TOC** for posts is enabled.
* **Profile** including your links and avatar on the sidebar.
* *And more...*

> **Tips:** You can disable Disqus or 多说 on posts/pages by adding `nocomments: true` into [YAML Front Matter][frontmatter].

EasyBook uses upaiyun CDN to make everyone lncluding Chinese visitors feel speedy. You can find it in `_includes/footer.html` and change it to your favorite CDN like Google CDN.

### Support the Developers ###

**Add a Link:** This website is using [laobubu](http://laobubu.net)'s theme: [EasyBook][github-easybook].  
**Donate:** Please visit [http://laobubu.net/donate.html](http://laobubu.net/donate.html).  
**Star and Fork on GitHub:** You can also send out your precious star [on GitHub][github-easybook].

## Support me by... ##

### Add a link ###

If my articles may have inspired you, a link adding will be appreciated. My site is [https://xpchen0630.github.io](https://xpchen0630.github.io).

### Star and Fork on GitHub ###

You can also send out your precious star [on GitHub](https://github.com/xpchen0630/xpchen0630.github.io).

## And Here We Go ##

My aritcles will mostly focus on machine learing (both theory and application). They can be seen as my reading notes and learning summary of the recent period. 
If you have any questions and doubts in reading them, please contact me by email (867813005@qq.com). It's my pleasure to discuss with you.

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[frontmatter]: http://jekyllrb.com/docs/frontmatter/
[github-easybook]: https://github.com/laobubu/jekyll-theme-EasyBook
