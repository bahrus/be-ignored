# be-ignored [TODO]

*[be-definitive](https://github.com/bahrus/be-definitive)* auto generates properties when defining a web component, based on the presence of itemprop attributes.

However, there are some HTML "signals" that we may not want to be turned into a public property whose values can be passed in.  One clear example of this is computed ["properties"](https://githuc.com/bahrus/be-sides).

So be-ignored is a reserved attribute which (for now) simply provides a semantic way of saying do not include in the list of public properties.  The attribute applies to the element it adorns, and any inner children.

*[be-linked](https://github.com/bahrus/be-linked)/[be-sharing](https://github.com/bahrus/be-sharing]* will also stay clear of such elements when applying binding.