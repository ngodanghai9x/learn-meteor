## Typescript:
- https://github.com/zodern/meteor-types#meteor-apps
- https://docs.meteor.com/using-core-types.html


Install TypeScript:

`npm install --save-dev typescript`
Initialize a TypeScript configuration file:

`npx tsc --init`
Update the tsconfig.json file:

Uncomment and modify the "outDir" option to specify the output directory for compiled TypeScript files.
Set the "module" option to "commonjs" to use CommonJS modules.
Set the "target" option to the ECMAScript version that your project supports.
Specify the TypeScript files to include and exclude, if necessary.
Install the necessary TypeScript typings for Meteor:

`npm install --save-dev @types/meteor`
Rename your existing JavaScript files to .ts or .tsx extensions to indicate that they are TypeScript files.

Start the TypeScript compiler in watch mode:

`npx tsc --watch`
Update your Meteor server and client entry points to use the compiled TypeScript files.

Install any additional TypeScript typings for external libraries that you use in your Meteor project.

Make sure to follow TypeScript syntax and type checking in your TypeScript files.

By following these steps, you can integrate TypeScript into your MeteorJS project and leverage the benefits of static typing and enhanced tooling provided by TypeScript.
