# <img alt="" src="https://cdn.rawgit.com/front-end-styleguide/brand/master/mark/mark.svg" width="24"> Front End Styleguide Templates

Templates for the different Front End Styleguide versions. These are used by the [CLI package](https://github.com/front-end-styleguide/cli) to quickly setup a working styleguide.


## Installation

```bash
# Yarn
yarn global add front-end-styleguide-cli

# npm
npm install -g front-end-styleguide-cli
```


## Project Creation

```bash
mkdir new-project
cd new-project
front-end-styleguide init
```


## Usage

```bash
# Start dev server
yarn dev
# or
npm run dev

# Build files for production
yarn build
# or
npm run build

# Build static styleguide with prototypes and components
yarn build:dev
# or
npm run build:dev

# Build static styleguide with prototypes only
yarn build:proto
# or
npm run build:proto

# Run linting
yarn lint
# or
npm run lint

# Run unit and e2e tests
yarn test
# or
npm run test
```
