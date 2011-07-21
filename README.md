# This is the speaker exchange Website

## How to set it up and run locally

 * go check it out with `git clone git@github.com:yourname/speakerexchange.git`
 * isntall jekyll with `gem install jekyll`
 * go into the checked out project and start jekyll with `jekyll --auto --server`
 * go to `http://localhost:4000` to see the site
 * change the site code which uses markdown (http://daringfireball.net/projects/markdown/syntax) to generate html but you can anytime use plain html aswell
 * review your changes by checking `http://localhost:4000`

Note:

There is a rake task. Run 

    rake default

to have compass watch the sass stuff, jekyll watch the html stuff, start a local webserver, and open firefox onto it.
