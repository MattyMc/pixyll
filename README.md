# Posting Guide (for Matt)

Some instructions on creating, building, deploying.

## FYIs

Create all posts in the ```_posts``` directory using 2011-12-31-new-years-eve-is-awesome.md file format
Use $ jekyll build or include the --watch flag to watch for changes (and build automatically)
Use $ jekyll serve --force_polling --drafts to launch a local web server.

## Some Markdown tips:

Use the following syntax for code highlighting (from Pygments):
{% highlight ruby %}
def this_is_my_code
	@instance_var = "hello"
  puts instance_var
end
{% endhighlight %}

## Categories
technical
essays

## Modifications

I've made some changes to the scss in _main.scss (at the bottom of the file)
