A set of Java APIs to programmatically validate your Web resources (HTML, CSS, etc).

Currently supports:
* Nu Validator (HTML4, HTML5, XHTML, etc..)  (access remote validator.nu - service can also be installed on own server)
** content upload
** by URL
* W3c validator (access remote w3c validator - service can also be installed on own server)
** content upload
** by URI
* CSS Validator (works without server, depends on https://github.com/lacostej/css-validator)
** by URI (file:// or http[s]://)
* Jsonlint validator (works online with remote server)
** by remote URI or content. In theory can support reformatting and compression. Features not enabled yet.
