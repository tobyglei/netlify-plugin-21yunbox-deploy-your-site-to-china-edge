# Fix Your Netlify Site in China

This Netlify Build Plugin is developed and powered by [21YunBox][1], and it helps you deploy your site to in-china Edge, and this plugin enables your site to load fast in mainland China.


## Usage
You can install this plugin in the Netlify UI from this direct in-app installation link or the [Plugins directory](https://app.netlify.com/plugins).

For file-based installation, add the following lines to your **netlify.toml** file:

```toml
[[plugins]]
package = "netlify-plugin-21yunbox-deploy-your-site-to-china-edge"
```

To complete file-based installation from your project's base directory, use npm, yarn, or any other Node.js package manager to add the plugin to devDependencies in `package.json`.

```
npm install -D netlify-plugin-21yunbox-deploy-your-site-to-china-edge
```

[1]: https://www.21cloudbox.com/