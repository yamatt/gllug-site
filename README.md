# GLLUG Site

A Hugo static site copy of the old Wordpress site with content migrated over.

## Running Locally

```sh
hugo server -D --bind=127.0.0.1
```

## Import

Get a Wordpress export, install uv and run `uv sync`.

```sh
uv run import.py import.xml content/posts
```