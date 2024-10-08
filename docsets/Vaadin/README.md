Vaadin Framework Docset for Dash
================================

Reference documentation for use with [Dash](http://kapeli.com/dash), an API Documentation Browser by [@kapeli](https://twitter.com/kapeli)

## About Vaadin

> Vaadin: thinking of U and I

> Vaadin is a Java framework for building modern web applications that look great, perform well and make you and your users happy.

Visit [https://vaadin.com/]() for more information about the project.

This is a compilation of the Javadoc API documentation available for download from Vaadin's website.

## About this Docset

This Dash docset was compiled by [Eric W. Wallace](https://twitter.com/ewall) and is available on [Github](https://github.com/ewall/Dash-User-Contributions/tree/master/docsets/Vaadin).

### Available Versions

* 8.26.0
* 8.25.2
* 8.20.3
* 7.7.7

### Generating this Docset

1. Download Javadoc jar for the latest Vaadin release from [https://vaadin.com/releases](), and extract the files.
2. Use [javadocset](https://github.com/Kapeli/javadocset) to compile the Docset, e.g. `./javadocset Vaadin <path to extracted Javadoc folder>`
3. Add the icon and enable JavaScript per [these instructions](http://kapeli.com/docsets).
4. Test the new docset in Dash to ensure it's working as expected.
5. Wrap up the files with `tar --exclude='.DS_Store' -cvzf Vaadin.tgz Vaadin.docset`, create version folder, and move the archive into it.
6. Don't forget to update `docset.json` and `README.md` files!
