An old version of LanguageTool browser extension that works with [a local instance of
LanguageTool](https://dev.languagetool.org/http-server).

## Building the Firefox extension

First, bump the version in `webextension/manifest.json`.

```
 export WEB_EXT_API_KEY=
 export WEB_EXT_API_SECRET=
```

```
web-ext sign --channel unlisted --source-dir webextension --artifacts-dir dist
```
