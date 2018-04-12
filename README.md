Cool CLI interface!

![Image of basis CLI](assets/basis.gif)

Ok now what? Lets check out the directory.

```
.
├── config
│   ├── build.config.js
│   ├── nginx.conf
│   ├── settings.default.js
│   ├── settings.development.js
│   ├── settings.local.js
│   ├── settings.production.js
│   ├── theme.js
│   └── webpack.config.js
├── gulpfile.babel.js
├── package.json
├── scripts
│   ├── deploy.sh
│   ├── install_deps.sh
│   ├── install_platform.sh
│   ├── nuke_packages.sh
│   ├── set_node_env.sh
│   ├── set_runtime_dir.sh
│   ├── start.sh
│   └── stop.sh
├── src
│   ├── client
│   │   ├── app.jsx
│   │   ├── components
│   │   │   ├── appBar
│   │   │   │   ├── appBar.jsx
│   │   │   │   └── index.js
│   │   │   ├── index.js
│   │   │   ├── section
│   │   │   │   ├── index.js
│   │   │   │   └── section.jsx
│   │   │   └── slidingPanel
│   │   │       └── slidingPanel.jsx
│   │   ├── index.js
│   │   └── modules
│   │       └── shell
│   │           ├── actions
│   │           │   ├── fetchConfig.js
│   │           │   └── index.js
│   │           ├── components
│   │           │   ├── settingsPanel.jsx
│   │           │   └── shell.jsx
│   │           ├── constants
│   │           │   └── actionTypes.js
│   │           ├── index.js
│   │           └── reducers
│   │               └── index.js
│   └── server
│       ├── assets
│       │   └── styles
│       │       └── main.scss
│       ├── bin
│       │   └── bootstrap.js
│       ├── modules
│       │   └── home
│       │       ├── homeController.js
│       │       └── index.js
│       └── views
│           ├── app.ejs
│           ├── head.ejs
│           └── index.ejs
├── test
│   ├── mocha.opts
│   └── server
│       ├── homeControllerSpec.js
│       └── homeIndexSpec.js
└── tsconfig.json

23 directories, 44 files
```
