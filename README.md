# Ampscript and SSJS Code Snippets
This repository conatins some Ampscript and SSJS code snippets documented for public reference.

## Sample Codes
* [How to execute HTTP GET Request in SSJS and Ampscript using Bearer Token Authentication in Header](http-get-function-with-bearer-token-header-request-using-ssjs-ampscript)

### Technologies Used
* Ampscript in Salesforce Marketing Cloud
* Server Side Javascript (SSJS) in Salesforce Marketing Cloud
* HTML, CSS and JavaScript

### Getting Started with Ampscript and SSJS
* Edit code on local machine using any IDE like Sublime, Visual Studio Code
* Install plugin to support Ampscript syntax - for better code readability

### Executing code
* Copy/Clone code
* Paste in Marketing Cloud's CloudPages or Email Templates or Content Blocks
* Publish changes
* Check Output

## Help
As a best practice, it is recommended to use the Try-Catch SSJS code block for all Ampscript code.
Paste below code above the start of the HTML file.
```
<script runat="server">
    Platform.Load("Core", "1.1.1");
try {
</script>
%%[
AMPSCRIPT CODE HERE
]%%
<script runat="server">
} catch (e) {
 Write("<b>Error Message:</b> " + Stringify(e.message) + "<br><b>Description:</b> " + Stringify(e.description));
}
</script>

```

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
