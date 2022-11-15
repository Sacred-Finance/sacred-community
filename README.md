# Sacred Community

This mono-repo was generated using [Nx](https://nx.dev). The repo holds back end contracts, relayers, etc that [community clients](https://github.com/Sacred-Finance/sacred-community-clients) can connect to.

## Getting started

Access the root directory

`npm install -g npx`

`npm install -g nx`

`npm install`

If you are using VS Code, install the recommended addons such as prettier.

## Repo structure

Most of the files are for scaffolding, so you only need to focus on the `/packages` folder which holds the different packages in this repo

Each app is stored under `/packages`

E.g.

`/packages/contracts`

`/packages/relayer`

etc

## NX Visual Studio Extension

This [official extension](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console) has the commands listed below, and more, to make things easier.

## Some useful commands:

### Generate a component

This will generate a new package called 'test'. Remove `--dry-run` to generate the actual files, and keep it to see a preview.

`nx g @nrwl/js:lib test --dry-run`

Generating a package this way also automatically creates testing for you.

See [here](https://www.youtube.com/watch?v=-OmQ-PaSY5M) for a quick tutorial

#### Run the dev server on your localhost

`nx serve <package>` e.g: `nx serve contracts`

#### Test a project

`nx test <package>` e.g: `nx test contracts`

#### Build a project

`nx build <package>` e.g: `nx build contracts`

### Other userful commands

https://nx.dev/packages/react#generators

#### Setup pipelines

https://nx.dev/recipes/ci/ci-setup
