# GLLUG Site

A Hugo static site copy of the old Wordpress site with content migrated over.

When the site is updated it builds the site using Hugo and pushes it to the `public` branch.

The server then had a cron job that pulls the latest version every 5 minutes and the directory that Apache uses is symlinked to the git repo.

There is also a `.htaccess` file in the `public` branch that turns the `.git` directory and any hidden files `.*` to 404s.

It also redirects the old `index.php` urls to native URLs.

## Running Locally

```sh
hugo server -D --bind=127.0.0.1
```

## Import

Get a Wordpress export, install uv and run `uv sync`.

```sh
uv run import.py import.xml content/posts
```
