HTML5 / CSS3 Framework
======================

HTML5
-----

Lorem ipsum...


CSS3
----

### Selectors


* #### Attribute Selectors

    * `[att^="value"]`  
      Match elements to an attribute that starts with the specified value   

    * `[att$="value"]`  
      Match elements to an attribute that ends with the specified value
  
    * `[att*="value"]`  
      Match elements to an attribute that contains the specified value
  
    * Example:  

            a[title$="tweetCC"] {
		        position: absolute;
		        top: 0;
		        right: 0;
		        display: block;
		        width: 140px;
		        height: 140px;
		        text-indent: -9999px;
		        }

* #### Combinators

    Targets all siblings of an element that have the same parent:

        div~img {
			border: 1px solid #ccc;
			}
			
* #### Pseudo-Classes

    * `:nth-child(n)`  
      Target elements based on their positions in a parent’s list of child
      elements. Can use a number, a number expression or the `odd` and `even`
      keywords:

            name="code">:nth-child(3n+4) { background-color: #ccc; }


