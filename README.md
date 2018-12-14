Symfony CLI Test
================


### Instructions

 * Run `yarn`
 * Start webpack dev-server on port 8000: `node_modules/.bin/encore dev-server --port=8000`
 * In another terminal, run Symfony web server: `symfony server:start --dir=src/test`

**Note**: The Symfony development server is started on port 8000 instead of 8001 (Since 8000 is already in use by the webpack dev-server)

