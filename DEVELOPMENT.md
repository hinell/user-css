
> Updated: Thursday, July 29, 2021

# Overview
A good starting point with contribution is to checkout root [`package.json`](./package.json) file scripts first.

# Folder structure

### `./`
* The root and sub-folders are maintananed by using following tools:
    | tool | description
    |-|-|
    | `npm`         | Versions & dependencies management |
    | `commitizen`  | Handy tool to quickly build up git commit message. Use it like|

* General life-cycle commands: 
    | command | description
    |-|-|
    |`$ npm run cz`| commit changes by using `git-cz` |
    |`$ npx lerna create <pkg name>`| create new userstyle |


### `./userstyles/`
* All `package.json` fiels inside this folder are intended to be used for isntalling extra css generators such as `.sass`.


