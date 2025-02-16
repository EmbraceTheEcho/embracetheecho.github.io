# embracetheecho.github.io
Source code for the band Embrace The Echo: a band of engineers in the 21st century

## How to contribute

### References

The site is built upon [chirpy-starter](https://github.com/cotes2020/chirpy-starter).
Edit the files in folder `_posts` and `_tabs` according to [these docs](https://github.com/cotes2020/jekyll-theme-chirpy/tree/fbba0a4204f6aea9816b92b357ccd0969d41c53f/_posts).

Important files and folders:

* `_config.yaml`
* `_tabs/about.md`: about tab
* `_posts/<article>.md`: content of the site
* `assets/`: the assets (icons, images, etc)
* `_data/authors.yml`: list of authors
* `_layout`: layouts for the pages

### Important branches

1. `main` branch: hosting the cutting edge, most updated version of our story. 
It previews the future of the blog.
2. `releases` branch: things that are published onto the World stage!
In engineering terms, the github workflow will look at the content of `docs`
folder inside this branch. When changes are made to this folder:

    * the workflow will run
    * if it is successful, changes will be reflected onto the github.io website

### Development flow

1. Create your changes on a branch, for example, `feat/guitarist/add-content-team`
2. Create a PR to merge your branch onto `main` and request other band members to review
3. If the changes are approved, merge the PR into `main`
4. Once the time comes to release, merge the changes from `main` to `releases` branch
5. Check that the github workflow builds successfully and the website is updated correctly

## How to preview the website locally to test changes

With some reference to [the chirpy full repo](https://github.com/cotes2020/jekyll-theme-chirpy/blob/b641b364809ea15c46d16ce1379a267d395d55d0/_posts/2019-08-09-getting-started.md#installation):

* Install ruby version (>3.1, preferably 3.3.4) with `rvm` manager
* Install the dependencies by running `bundle`
* Run `bundle exec jekyll s` and the local site will be available at `http://127.0.0.1:4000`
