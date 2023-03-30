
# Remove All External Links in any website/post using Javascript.
Remove All Links in a webpage after finished loading excluding the internal links as well as some whitelisted domains.
This JavaScript code removes the link and retain its text text for all external links on a web page except for a few excluded domains. It is useful for websites that want to avoid promoting external links that may be irrelevant or not in line with the website's content.
## Installation

To use this code, you can copy and paste it into a JavaScript file or add it directly to an HTML file within a script tag.
## Usage

The code will automatically run when the web page loads and remove the link text for all external links except for the domains specified in the excludedDomains array. If you want to modify the excluded domains, you can add or remove domains from the array.
## Example

Suppose you have a website with various external links, but you only want to show the link text for a few trusted domains such as Google and Wikipedia. You can use this code by adding the following line to your HTML file within a script tag:

### js

>const excludedDomains = ['google.com', 'wikipedia.org'];

- This will remove the link text for all external links except for those from Google and Wikipedia.
- Any links without http or https will be excluded as well
# Made With ❤️ By Innocent kisheo
