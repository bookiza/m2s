<div align="center">
  <a href="https://bookiza.io">
    <img src="h2s.jpg" alt="Tech Interview Handbook" width="400">
  </a>
  <br>
  <h3>
    <a href="https://bubblin.io/blog/h2s">Read the blogpost.</a>
  </h3>
</div>


# H2S

Usage: `$ h2s [options] [command]`

Options:
  -V, --version      output the version number
  -v, --version      output the version number
  -h, --help         output usage information

Commands:
  1. $ h2s objectify|o        # Objectify into a Array-like Json
  2. $ h2s pagify|p           # Paginate with gadda-gadda line-tracking!
  3. $ h2s bookify|b          # Templatize markup with layout to form actual pages


Installation:

```
$ npm i -g h2s

$ h2s --help 		# Vocabulary


```

Steps:

1. Place `sanitized.html` at `./interim` folder (sibling to the `manuscript` folder at the root of your [Bookiza](https://bookiza.io) project). 

2. Execute `$ h2s objectify` to pull up the contents into a set of key: value pairs. 

3. Run `$ h2s pagify` to paginate the key: value pairs according to a responsive template at `./templates` folder.

5. Run `$ h2s bookify` to apply layout on paginated content and produce book. And voila, your Superbook is ready!

Run `$ bookiza server` to start server and test the book on `localhost:4567`


