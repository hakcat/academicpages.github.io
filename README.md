## ReadME
My website, created with the help of [Academic Pages](https://www.academicpages.github.io) and [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under MIT License.  
The site is hosted with github as backend using **netlify**.

### Note: What is what
[`_data`](/_data/) contains  Navigation.yml: edits the top menu bar.  
[`_includes`](/_includes/) and `_layouts` Describe the html files. tweak at your own risk.  
[`_pages`](/_pages/) Create markdowns here to edit existing pages and create new ones. **Main element**  
[`_portfolio`](/_portfolio/) contains portfolio markdown and the corresponding html.
[`_posts`](/_posts/),[`_publications`](/_publications/), [`_talks`](/_talks/) and [`_teaching`](/_teaching/) contain respective markdowns. Just Simply edit them.  
[`_assets`](/_assets/) contain css, js and fonts






If you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

### To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above.  
2. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`.  
3. Run `bundle clean` to clean up the directory (no need to run `--force`).  
4. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.  
5. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.  

# References:
https://github.com/hakcat/academicpages.github.io/blob/master/_pages/markdown.md   
https://blog.mvp-space.com/10-steps-to-configure-jekyll-with-netlify-as-a-cms-d754d73ea731  
https://youthful-swartz-ca3262.netlify.com/   
https://en.support.wordpress.com/markdown-quick-reference/
