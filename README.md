
## test IO sideprojects

### Development

Run Jekyll:

    bundle exec jekyll serve

## Deploy to GitHub Pages

Before you deploy, commit your changes to any working branch except the `gh-pages` one then run the following command:

    bin/deploy

**Important note**: Chalk does not support the standard way of Jekyll hosting on GitHub Pages. You need to deploy your working branch with the `bin/deploy` script. This is because Chalk uses Jekyll plugins that aren't supported by GitHub pages.

[View this](https://github.com/nielsenramon/kickster#automated-deployment-with-circle-ci) for more info about automated deployment with Circle CI.
