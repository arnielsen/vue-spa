// Inital setup

Add files
- LICENSE
- README.md
- index.html (add boilerplate HTML)
- .editorconfig
- package.json

Open GitBash
- npm install vue@2.4.2 --save
- npm install express@4.15.4 --save

Add files
- server.js

Add folder
- build

Add files to build folder
- webpack.base.config.js

Open GitBash
- npm install webpack@3.5.5 --save-dev

Add folder
- src

Add files to src folder
- client-entry.js
- app.js

Open GitBash
- node ./node_modules/webpack/bin/webpack --config ./build/webpack.base.config.js

Open GitBash
- npm install webpack-dev-middleware@1.12.0 webpack-hot-middleware@2.18.2 --save-dev

Add file to build folder
- dev-server.js

Add file to build folder
- webpack.client.config.js

Add files
- .eslintrc.js

