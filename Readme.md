Dokku x86 buildpack: Python
========================

This is buildpack is based on the original [Heroku Python buildpack](https://github.com/heroku/heroku-buildpack-python). The python runtimes have been replaced with x86 ones create with pyenv (python-build). 


Provided Runtimes
-----------------

Runtimes are hosted on Github
For a list of runtimes please check [python-versions.txt](https://github.com/patrickjahns/python-herokuish-x86-packages/blob/dist/python-versions.txt)

The hosted runtimes are not intended for production use. If you want to use it in production, please download the runtimes and host them yourself. Don`t forget to modify [bin/steps/python](bin/steps/python) to link to your private repository


