# abizern.dev site in Hugo with ox-hugo

## Content

I'm using the one big Org file approach.

I've set it up to auto update for preview: start the server with `hugo server -D --navigateToChanged`

## Theme

I'm using Hugo-Coder but not as a submodule. The hugo site is set up as a module and the theme is a dependency. When cloning this repo you'll need to run `hugo mod get` to fetch the dependencies or `hugo mod get -u` to update everything.

## Generation

just run `hugo` and it will update the public folder.

## Deployment

Just ftp the `public` directory to the server.

Be careful, you may need to keep the content and the content.org synced. Deleting subtrees does not delete the content.

It may seem like overkill, but that is why I'm keeping the actual site contents in the generating repository.
