# Johnny Extension Pack

## How to add more extensions

You can now start adding extension ids into the `extensionPack` propriety in the `package.json` file. You can find extension ids at the end of the extension url. For example, the link to GitLens extension marketplace is https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens and the id is eamodio.gitlens.

## How to package

> Make sure you have [vsce](https://www.npmjs.com/package/vsce) installed

To generate a VSIX file that will let you install the extension pack, use the command below:

> `vsce package`

## How to install

Double click on VSIX file to install. If the installation fails, install it from within VSCode. Follow the steps to install manually:

- Select Extensions (Ctrl + Shift + X)
- Open “More Action” menu(ellipsis on the top) and click “Install from VSIX…”
- Locate VSIX file and select
- Reload VSCode
