# Scraper Data Examples

This is a guide for getting started with Vergil, Directory, and Handshake Data

[Directory Scraper](https://github.com/graphicsdesk/directory-scraper)
[Vergil Scraper](https://github.com/graphicsdesk/vergil-scraper)
[Handshake Scraper](https://github.com/graphicsdesk/lionshare-scraper)

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

3. If you're using Python: Run `pipenv install` to install the necessary packages. Run `pipenv shell` to launch the virtual environment and get access to those packages.

4. In the shell, run do `python -m ipykernel install --user --name=scraper-kernel`

5. Open up jupyter notebook and change the kernel

## Usage

Open up jupyter notebook and test out the scrapers!
