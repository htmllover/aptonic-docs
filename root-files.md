### Root files

There also a few files sitting at the root of the project that we need to discuss before getting into serious business:

- `gulpfile.js` : Gulp will use this file to perform all the tasks it is supposed to accomplish.
- `package.json` : Lists all your project's dependencies and gives useful metadata.
- `package-lock.json` :  Automatically generated for any operations where `npm` modifies either the `node_modules` tree, or package.json. It describes the exact tree that was generated, such that subsequent installs are able to generate identical trees, regardless of intermediate dependency updates.
