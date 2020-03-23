<div align='center'>

<br />

<img src='https://raw.githubusercontent.com/eclipse-theia/theia/master/logo/theia.svg?sanitize=true' alt='theia-ext-logo' width='100px' />

<h2>THEIA - APPLICATION-MANAGER</h2>

<hr />

</div>

## README

This package contains the generators used when creating a Theia application through `@theia/cli`.

This package can auto-generate application code for both the backend and frontend, as well as webpack configuration files.

When targeting Electron, the `electron-main.js` script will spawn the backend process in a Node.js sub-process, where Electron's API won't be available.
To prevent the generated application from forking the backend, you can pass a `--no-cluster` flag, or set an environment variable like `THEIA_ELECTRON_NO_BACKEND_FORK=1`.

```sh
# when developing a Theia application with @theia/cli:
yarn theia start --no-cluster

# when starting a bundled application made using @theia/cli:
bundled-application.exe --no-cluster
```

## Additional Information

- [Theia - GitHub](https://github.com/eclipse-theia/theia)
- [Theia - Website](https://theia-ide.org/)

## License

- [Eclipse Public License 2.0](http://www.eclipse.org/legal/epl-2.0/)
- [一 (Secondary) GNU General Public License, version 2 with the GNU Classpath Exception](https://projects.eclipse.org/license/secondary-gpl-2.0-cp)

## Trademark
"Theia" is a trademark of the Eclipse Foundation
https://www.eclipse.org/theia
