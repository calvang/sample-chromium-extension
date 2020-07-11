# Sample Chromium Extension

A boilerplate template for a simple React Chromium Extension

### Description

This repository and its Typescript counterpart were intented as tests for basic Chromium extension functionality for use in other projects. They are meant to be simple boilerplate templates and lack any features.

### Usage

This was created using `create-react-app` and is non-ejected, so be wary of creating multiple files with React code. 

To install dependencies, execute:
`npm install`
To deploy to production, execute:
`npm run build`
This can be deployed to Chrome and other Chromium-based browsers by navigating to `chrome://extensions` and choosing to "Load unpacked." Simply drag and drop your build folder to deploy.

### Building from scratch

To build this from scratch, run:
`npx create-react-app <appname>`
Then copy the manifest.json from this repository and replace the auto-generated one.
Then, to avoid errors, prepend `INLINE_RUNTIME_CHUNK=false` to the build command in package.json. 