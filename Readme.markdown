# abizern.dev site in Hugo with ox-hugo

## Content

I'm using the one big Org file approach.

I've set it up to auto update for preview: start the server with `hugo server -D --navigateToChanged`

## Deployment

Just ftp the `public` directory to the server.

Be careful, you may need to keep the content and the content.org synced. Deleting subtrees does not delete the content.

It may seem like overkill, but that is why I'm keeping the actual site contents in the generating repository.