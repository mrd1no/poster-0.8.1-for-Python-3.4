# poster-0.8.1 for Python 3.4
This repository contains a poster version working in Python 3.x
I wanted to use an API from https://www.mashape.com but their library (<a href="https://github.com/Mashape/unirest-python"><b>unirest</b></a>) requires poster >=0.8.1 (available in 2.x only). 

Since poster has not been released for Python 3.x, I did some workarounds using 2to3 and changing urllib methods manually.

Like the original package, this repository contains:

setup.py <br>
poster/__init__.py  <br>
poster/encode.py  <br>
poster/streaminghttp.py  <br>
poster.egg-info/PKG-INFO  <br>
poster.egg-info/SOURCES.txt  <br>
poster.egg-info/dependency_links.txt  <br>
poster.egg-info/requires.txt  <br>
poster.egg-info/top_level.txt  <br>
poster.egg-info/zip-safe  <br>
tests/__init__.py  <br>
tests/test_encode.py  <br>
tests/test_server.py  <br>
tests/test_streaming.py <br>

After downloading it, you can normally install it using from the command line <i>setup.py install</i>

Please note this is not an official distribution of the package and I don't have any copyright on it.
