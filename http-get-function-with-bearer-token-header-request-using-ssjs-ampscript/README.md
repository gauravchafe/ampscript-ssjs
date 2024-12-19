# How to execute HTTP GET Request in SSJS and Ampscript using Bearer Token Authentication in Header

## Description

This file contains SSJS and Ampscript code for executing a HTTP Get Request using Bearer Token Authentication in Header

## Key Information for this use case

* [HttpGet()](https://developer.salesforce.com/docs/marketing/marketing-cloud-ampscript/references/mc-ampscript-http/mc-ampscript-reference-http-get.html) in Ampscript does not support header values, and hence we need to use the [HTTP.Get()](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ssjs_platformContentSyndicationHTTPGet.html) in SSJS to execute the GET Request.
* The response from the GET Request is in JSON format. There is no function in Ampscript to Parse JSON. Hence, we need to use the [ParseJSON()](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ssjs_platformUtilityParseJSON.html) in SSJS to parse the JSON response and then forward the data to Ampscript using [SetValue()](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ssjs_platformAMPscriptVariableSetValue.html) SSJS function.

## Author

Gaurav Chafe 
[X](https://x.com/gauravchafe) | [LinkedIn](https://in.linkedin.com/in/gauravchafe)

## License

None - Code is for public use

## Acknowledgments

Inspiration, code snippets, etc.
* [Salesforce Developers](https://developer.salesforce.com/docs/marketing/marketing-cloud-ampscript/guide/mc-ampscript-get-started.html)
* [Salesforce Trailhead](https://github.com/dbader/readme-template)
* [Ampscript Guide](https://trailhead.salesforce.com/content/learn/trails/code-with-ampscript)
* [Ampscritify](https://b2shashi-mc.github.io/ampscript/)
