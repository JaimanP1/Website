# Instructions

Using Hugo to build the site.

## New page
In the root git directory, do `hugo new dir/page.md`

Note that the `dir` refers to the specific `content/dir/`, but `content/` is omitted.

## Push to gh pages
First commit to `main` and push to remote.

Workflow is set up in yaml file in .github/

## Rebuild
Make sure toml file correctly reflects layout and pages are not drafts

Then run `hugo` and check to see if `hugo server` works
