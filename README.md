# Scraper Data Examples

This is a guide for getting started with Vergil, Directory, and Handshake Data. The links to the repos of the scrapers can be found below.

* [Directory Scraper](https://github.com/graphicsdesk/directory-scraper)   
* [Vergil Scraper](https://github.com/graphicsdesk/vergil-scraper)  
* [Handshake Scraper](https://github.com/graphicsdesk/lionshare-scraper)  

## Setup

1. Clone the repository and move into it:

```
$ git clone git@github.com:NewsroomDevelopment/scraper-examples.git
$ cd scraper-examples
```

2. Create a `.env` file with the contents below. (See this [Google Doc](https://docs.google.com/document/d/1C6WPRpabD6YXjQK3VnvjGy02fgxaARHbJTirm3Rzf8I/edit) for the MongoDB user credentials.) Make sure `.env` is always listed in your [`.gitignore`](https://guide.freecodecamp.org/git/gitignore/) file.

<pre>
# MongoDB credentials

MDB_USERNAME=<var>USERNAME</var>
MDB_PASSWORD=<var>PASSWORD</var>
</pre>

3. Follow [this tutorial](https://github.com/graphicsdesk/graphicsdesk.github.io/wiki/AWS-Setup) to set up the aws credentials needed for some of the scrapers. 

4. If you're using Python: Run `pipenv install` to install the necessary packages. Run `pipenv shell` to launch the virtual environment and get access to those packages. If you do not have `pipenv` do `pip install pipenv`. If you do not have `pip` look it up.

5. In the shell, run do `python -m ipykernel install --user --name=scraper-kernel`

6. Open up jupyter notebook and change the kernel by going to kernel -> change kernel -> scraper-kernel.

## Usage

Open up jupyter notebook and test out the scrapers!
