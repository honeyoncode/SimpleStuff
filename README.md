# Simple Stuff
Simple Stuff is a collection of things.

What things?

Anything I feel like collecting.

Simple Stuff is supposed to be a human-managed collection of things I thought were interesting or important. Basic recipes that everybody should know, how-to guides on doing things like making websites, directories to places that can explain things better than I ever could, that sort of thing.

The site is minimalistic, with the focus being on the content. There is no JavaScript*, no cookie tracking necessary, it's just a simple website.

*Technically I use JavaScript for site generation, as this site is made using something called 11ty which helps me build the site, but by the time the site is deployed to the server it's just a collection of HTML and CSS (and images).

## Running locally
If you want to run this locally, after cloning or forking the repo you'll firstly want to do `npm i` to install the packages.

To run it, type `npm run serve`. This is an alias I set up in the `package.json` file for `npx @11ty/eleventy --serve`, eleventy being the static site generator I'm using.