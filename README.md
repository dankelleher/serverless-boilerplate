## Serverless Boilerplate

A boilerplate codebase for serverless projects using the Serverless Framework.

This code is set up for the following:
- ES6 syntax (webpack + babel)
- Unit testing with mocha and chai
- Integration testing with newman

I suggest you run `yarn upgrade` before starting work on this.

The webpack configuration creates output for all files in the `src` folder with 
names ending in `*Handler.js`. The output files are all generated in the `dist`
folder, so ensure the handlers have unique filenames. 