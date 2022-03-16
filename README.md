# FACS2022
Website of the FACS2022 conference

To run the website locally, see https://jekyllrb.com/docs/

    gem install jekyll bundler # run this one time
    bundle add webrick # ditto, for ruby 3.0 or higher
    bundle add leaflet
    bundle exec jekyll serve --livereload # to start jekyll
    
When jekyll is running, open http://localhost:4000 to see the website.

To serve for other IPs, use e.g.:

    bundle exec jekyll serve -H 100.111.101.124 --incremental
