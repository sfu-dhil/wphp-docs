# Documentation for WPHP       
This is the documentation repository for the Womens Print History Project Database.

## How to create the documentation

_(Note: The following instructions assumes you're using a Mac)_

### Step 0: Getting Homebrew

First, make sure you have Homebrew on your local system by going into the command line and typing:

```
brew --version
```

If you get something like:

```
Homebrew 2.2.4
Homebrew/homebrew-core (git revision 6915; last commit 2020-01-20)
```

You're good to proceed to step 1.

If not, then download Homebrew following the instructions on its homepage: [http://brew.sh/](http://brew.sh/)

Once homebrew is installed, then download 

### Step 1: Getting Sphinx

Sphinx is a Python based documentation generator. To use Sphinx, you must have Python 3 installed as well as Sphinx.

First download Python:

```
brew install python3
```

Then download Sphinx using `pip`:

```
pip install sphinx
```

### Step 2: Building the Documentation

Once you have the repository on your machine locally, you can run:

```
make html
```

Which will generate HTML pages from the RST files in the `source/` directory. 

Those files are stored *ONE LEVEL ABOVE* your `wphp-docs` folder. So if you have your `wphp-docs` directory in `Sites`, the documentation will be in:

`Sites/web/docs/sphinx/index.html`

From there you can navigate around the documentation.

**Note**: Run `make html` often and watch the output in your terminal; it only takes a few seconds and it will tell you if you've made any errors in the structure of the RST markup.





