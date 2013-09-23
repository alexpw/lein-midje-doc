# lein-midje-doc

`lein-midje-doc` fixes the problem of incorrectly documented examples by bridging the gap between writing tests and writing documentation.

Visit the [main site](http://z.caudate.me/lein-midje-doc/) for more information.

### Features:
 1. To generate `.html` documentation from a `.clj` test file.
 2. To express documentation elements as clojure datastructures.
 3. To render clojure code and midje facts as code examples.
 4. To allow tagging of elements for numbering and linking.

### Benefits:
 1. All documentation errors can be eliminated.
 2. Removes the need to cut and copy test examples into a readme file.
 3. Entire test suites can potentially be turned into nice looking documentation with relatively little work.

### Wishlist:
- Latex Features
  - Table of Figures
  - Table of Examples
  - Citations
  - Customisation Numbering
  - Appendices
  - Equations  
- Themes
- Elements
  - `:reference` element for tabulization of ns-publics in a namespace 
- Attributes
  - `:ignore`
- Linking to Multiple Documents (Generate an entire Site)
- Additional Test Suites
  - core.test
  - purnam.test
- pdf output with page numbering
- markdown output
- Codebase
  - Refactor with multimethods
  - Clean up hacked-in code
  
## License

Copyright © 2013 Chris Zheng

Distributed under the The MIT License.