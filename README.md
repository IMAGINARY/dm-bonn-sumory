# dm-bonn-sumory

Deutsches Museum Bonn version of the Sumory exhibit

## Building

Requires Node.js (v18.19 or greater) and npm.

Run the following from the root directory of the project:

```bash
npm install
npm run build
```

This will create a `dist` directory with the compiled exhibit. This directory can be served by any web server.

## Development

To ease development you can run two separate tasks in parallel: `watch:copy` and `watch:compile`

The first one will copy any changes within ./extras to ./dist, while the second one will recompile 
the exhibit after the changes are copied.

## Credits

This adaptation was developed by Eric Londaits for Imaginary gGmbH.

## License

Code licensed under the MIT License. See [LICENSE](LICENSE) for details.

Copyright 2024 Imaginary gGmbH.
