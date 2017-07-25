# re-playground

Static web editor to share documentation code and mess around with small re-frame experiments!

Code is livereloaded with [klipse plugin](https://github.com/viebel/klipse). The right-hand panel has the id 'app'. To render reagent into this panel, target this element with `(js/document.getElementById 'app')`.

See the [examples]()!


## load from gist

To easily share re-frame sketches, you can save your code to a github gist and load it into this editor with the url param: `gist-id=[github-username]/[gist-id]`

For example: `?gist-id=daiyi/62db9d22136503a42cbbe5dc5ec0337d`

The whole url would look something like: `https://sample-site.net?gist-id=daiyi/62db9d22136503a42cbbe5dc5ec0337d`


## developing

Clone this project and enter the folder:

```
git clone git@github.com:Day8/re-playground.git
cd re-playground
```

Serve the static page with python:

```
python -m SimpleHTTPServer
```

The page should be available at [http://localhost:8000]!
