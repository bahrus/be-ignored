# be-ignored

*[be-definitive](https://github.com/bahrus-be-definitive)* auto generates properties when defining a web component, based on the presence of itemprop attributes.

However, there are some HTML "signals" that we my not want to turned into a public property whose values can be passed in.  One clear example of this is computed "properties".

So be-ignored is a reserved attribute which (for now) simply provides a semantic way of saying do not include in the list of public properties.  The attribute applies to the element it adorns, and any inner children.