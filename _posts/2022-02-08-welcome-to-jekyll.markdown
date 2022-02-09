---
layout: post
title:  "My discovery of Jekyll and the world of writing a blog"
date:   2022-02-08 17:46:30 +0100
categories: jekyll update, hack
---

So this is a first post. It’s actually more a training field for me to play
with Jekyll.

I will let the orignal engine documentation bellow, it might serve me well in
the near future, and who knows, maybe others?

Anyway I don’t have yet precise topics I want to discuss on my very own blog,
and to be honnest this is rather an alien practice to me. I’m more accustomed
to publish things on the form of "research project" with unpersonal tone. Like
the [*Sur l’extension des genres grammaticaux en français*](https://fr.wikiversity.org/wiki/Recherche:Sur_l%E2%80%99extension_des_genres_grammaticaux_en_fran%C3%A7ais).
Oh, yes, since French is my mother tongue it is also the one I most often write
into my prose. I might switch here and there, but since chances are good that
I write here to unleash opinions and share experiences on CS/IT stuffs, whose
vehicular language is English, I will probably mainly stick with that.

So yesterday, as I’m actually writing that on the 9 February, editing the first
blog post Jekyll created for me, while making my daily [HN](https://news.ycombinator.com/)
watch, my eyes where catched by the entry [Human technology: Text files](https://boris-marinov.github.io/text/).
In this blog post by Boris Marinov made me discover Jekyll and how easy it was
to maintain and publish a blog using my familiar dev tools. So this is it, I
can write some Markdown in my beloved Vim/Neovim and `git push` to Github to
get there. To be honnest, it took me a bit more of perseverance, as I was sitting
at the time before an almost naked Windows box. So I had first to:
- install Ruby – one of my favorite programming language anyway
- setup a descent command line, with [WSL2](https://docs.microsoft.com/en-us/windows/wsl/about), [Alacritty](https://alacritty.org/), [Fish](https://fishshell.com/), and so on
- fix an issue that prevented to run `bundle exec jekyll serve` from a git bash prompt with Ruby 3.0.

Anyway, all in all it worked, and here we are, a few commits later, ready to
publish something.

Bellow is the original post, prefilled by Jekyll
--------

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
