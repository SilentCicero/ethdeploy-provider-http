# Changelog

## ethdeploy-provider-http | 0.1.0

This is the first provider module for ethdpeloy. Very much in the webpack philosophy, providers can now be created and deployed to the system. The provider can be specified in the ethdeploy module by specifying for example: `http` which then requires the JS module `ethdeploy-provider-http`.

If you would like to create your own provider, just module.export a function that returns the provider object, and intakes a single provider object variable. An API will be specified in the ethdpeloy docs.
