*Infinite Jest* co-reading notes
================================

To play along, you'll need:

* a copy of *Infinite Jest*;
* [nanoc](https://nanoc.ws/); and
* [kramdown](https://kramdown.gettalong.org/)


What's this all about?
----------------------

It's about *Infinite Jest* by David Foster Wallace. We love this book. And/but/so: we are (re-) reading it. These are our notes. Feel free to fork, patch, contribute, and/or what have you.

How do I... play?
-----------------

Make notes. Write essays. Connect the dots. Go nuts. It's free-form.

Eh, ok. How do I use nanoc for local development?
-------------------------------------------------

First, install the Ruby¹ gems  `nanoc` and `kramdown`:

    gem install nanoc kramdown

The gem nanoc comes with an own executable called `nanoc`.
If you made changes and want to regenerate the whole
site locally, you need to run

    nanoc

in the folder of this repo. If everything went fine and you haven't got any
erros, you can start a webserver via

    nanoc view

You can view your version of Infinite Notes in you browser via

    http://localhost:3000

--

¹) Of course this implies you have installed [Ruby](https://www.ruby-lang.org). If you haven't, _this_ is _your moment_
to get in touch with it.
