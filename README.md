# Website

[ICES](https://www.ices.one/)


ICES (Internet Computer Event System) is a canister custom event log storage and analysis service on Dfinity. It mainly solves the problem that canister's interaction records cannot be publicly queried. Any canister can access ICES without permission, store the interactive data permanently, and query it through the public API and dashboard provided by ICES.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
