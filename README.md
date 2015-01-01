# Investigation of problem with interpolating variables in a tag

An experiment to determine why using a page variable from
another page inside a for loop does not work when
sent to a liquid tag.

The problem lies in interpolating the passed in
variable from the loop in the proper context.

The plugin used was
[flickr_photoset](https://github.com/j0k3r/jekyll-flickr-photoset).



