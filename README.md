# [babel/website](https://babeljs.io) - Take a look at it

This is the source for the [babeljs.io](https://babeljs.io) website; feel free to suggest changes to our docs!

- Current: `master` branch is deployed to https://babeljs.io
- Old: `old-site` branch is deployed to https://old.babeljs.io

### Setup

```bash
$ git clone git@github.com:babel/website.git
$ cd website
$ yarn && yarn bootstrap
```

- Just run `yarn start` next time (check the package.json for scripts).

### Contributing to the website

To keep documentation in sync across all of Babel's packages, the docs are now directly located in this repository. The READMEs in [`babel/babel`](https://github.com/babel/babel) are [auto generated](https://github.com/babel/babel/blob/master/scripts/generators/readmes.js) and point to this documentation.

You might want to make yourself familiar with [docusaurus](https://docusaurus.io/docs/en/installation) to make significant changes to the website. If you only want to make content changes you just need to know about versioned docs.

#### Versioned docs

- `/docs` - the files in here are responsible for the "next" version at https://babeljs.io/docs/en/next.
- `/website/versioned_docs/version-*` - these are the docs for the past versions, the latest one being the currently published version at https://babeljs.io/docs/en

After making your changes to the markdown files in the `/docs` folder, a git hook script will suggest files from the past versions folders that you might also need to apply your changes to.

#### Looking for support?

For questions and support on contributing please join our [Slack community](https://slack.babeljs.io/), channel `#website` or directly [here](https://babeljs.slack.com/messages/website).
