# Example Amplify App

Intended to act as an example for https://github.com/CycloneDX/cyclonedx-node-npm/issues/81


To hit the npm ls error, just run `npm run build:bom` and it will fail. Interestingly, if you have a global install of cyclonedx-npm and run  `cyclonedx-npm --output-file bom.json` it will print the errors, but work. It will fail due to https://github.com/aws-amplify/amplify-ui/issues/2089
