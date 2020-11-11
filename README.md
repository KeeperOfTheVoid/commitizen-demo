# Commitizen Demo

This project is to test the commit tool Commitizen.

Commitizen is a tool that allows you to follow semantic template.

The only thing that is weird is that Angular team doesn't like multi line body descriptions.  

## Husky

Husky is a git hooks tool that allows you to do many things, like commit linting, running tests, etc.

## Standard Version

Standard Version is a way to generate CHANGELOGs.  As a result, it's super easy to tag and release code. 

For first time tag, run `yarn run release -- --first-release`.

For a dry-run, run `yarn run release -- --dry-run`.  This is useful to check what's actually getting put in your CHANGELOG.

Then, you run `git push --follow-tags origin master`.
