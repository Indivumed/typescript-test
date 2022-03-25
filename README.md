Our frontend is rendering patient interview forms for each of our clinics based on a json file (`/src/input.json`). This enables us to quickly adjust the potentially collected data for each of our clinics. For one of our internal e2e tests we now require the form fields as a flat array (`/src/output.json`). 

# TypeScript Code Challenge
Write a function that takes the `input.json` and returns the data in the format of the `output.json`.

## Boilerplate setup
- Install NodeJs V14 or newer
- You might need to install ts-node globally `npm install -g ts-node`
- Install the project dependencies
```
npm install
```
- To run the project on watch mode
```
npm run dev
```
- To run the test
```
npm run test
```

In the main.ts file in the src directory, we have defined a function traverseMetaData(inputMetaData).
This function takes the contents of input.json as parameter. Update the function so that all leafs from the tree structure in the `input.json` file are extracted into a list. A leaf by definition has no children. The resulting JSON should only contain leafs. The returned object should be similar to the serialized output.json.


All the best for the code challenge. Looking forward to the solution.
