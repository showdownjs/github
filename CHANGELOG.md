<a name"1.0.0"></a>
## 1.0.0 (2015-06-03)

#### Release information

This release updates the extension in order to make it compatible with showdown v.1.0.x.
However, this version is not compatible with older versions of showdown.
Since github-extension was previously bundled with showdown, with versions prior to v 1.0.x, use the bundled version instead.

#### Compatibility

**Compatible with showdown v.1.0.x

#### Features

* **bower.json**: add dependencies to bower json
* **package.json**: add dependencies to package.json

#### Breaking changes

* **renamed files**: src file renamed to `showdown-github.js`.
  To update, if your using src files directly, change your dependencies from `github.js` to `showdown-github.js`
