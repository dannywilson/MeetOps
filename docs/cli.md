# Use these yourself

`npm i @meetops/cli --save-dev` | `yarn add @meetops/cli -D`

All the following commands can be run either via:

* `npx meetops {command}` when using npm >= 5.0
* `yarn meetops {command}`

If running on npm < 5.0 either install globally `npm i @meetops/cli -g`

* `meetops {command}`

or

add `"meetops": "meetops --",` to your `package.json` scripts then use

* `npm run meetops {command}`

## Command List

* `-h, --help` - show cli tool help
* `-v, --version` - show cli version
* `init` - setup folder structure and walk through some intial settings
* `use {function-name}` - copy down the latest version of the function
    from git, where `function-name` is the sub directory name, under the functions folder
* `set` - set a configuration option (saved in meetops.js)