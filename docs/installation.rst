Installation
============


Using pip::

$ pip install ipyleaflet
$ jupyter nbextension enable --py ipyleaflet


Using conda::

$ conda install -c conda-forge ipyleaflet


For a development installation (requires npm)::

$ git clone https://github.com/ellisonbg/ipyleaflet.git
$ cd ipyleaflet
$ pip install -e .
$ jupyter nbextension install --py --symlink --user ipyleaflet
$ jupyter nbextension enable --py --user ipyleaflet

Note for developers: the `--symlink` argument on Linux or OS X allows one to
modify the JavaScript code in-place. This feature is not available
with Windows.
