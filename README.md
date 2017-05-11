# JStextgrabber
Cross-origin text-parser for use on static websites (like on Amazon's S3)
### Usage Example
A frequently updated text file containing a daily message can be stored on a cloud storage site like Dropbox. JStextgrabber on an S3 static website will grab the text file for parsing, then update the page dynamically without need for server-side processing.
#### Pros
* No need for a dynamic website (PHP, Django, etc.)
* Minimal gets/puts to static website, since text file is stored elsewhere (Lower usage for S3)
* Fast & Expandable
#### Cons
* Client is required to use javascript
* Probably not best for high-traffic uses
* Cross Origin Resource Sharing rules can be tricky
* Text file is open to the public (no sensitive data or logins)

### Live Examples
http://caffsushi.com/everydays
