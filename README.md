# embracetheecho.github.io
Source code for the band Embrace The Echo: a band of engineers in the 21st century

## How to contribute

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
