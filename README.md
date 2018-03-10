# Emmet HTML Snippets Cheatsheet

Snippet then tab or enter

### Base Elements

> *   `div`
> *   `h1`
> *   `p`
> *   `nav`

### Id and Class Attributes

Add '.' followed by classname

> .container -> div with a class of container

> div.container -> div with a class of container

> h3.text-center -> h3 with class of text-center

> div.container.flex-container -> div with class of container AND flex-container

Add '#' followed by id

> #mainContainer -> div with id of mainContainer

> div#mainContainer -> div with id of mainContainer

> h1#header -> h1 with id of header

Combine class and id

> div.container#mainContainer -> div with class of container and id of mainContainer

> h1.text-center#header -> h1 with class of text-center and id of header

### Multiplications

> h1\*3 -> 3 h1's

> li\*3 -> 3 li's

### Numbering

use the '$' operator combined with a multiplication to apply an index to an element

> ul>li.item$\*5 -> ul with 5 elements that have classes of item1, item2, etc.

### Child

Use '>' to add children

> div>h1 -> div with a child of H1

> ul>li -> ul with child of li

> ul>li\*3 -> ul with 3 li children

### Sibling

Use '+' to add siblings

> div>h1+p -> div with two children, h1 and p

> ul>li+li -> ul with two li children

> form>input:text+input:text+input:submit -> form with two text input children and a child submitt button

### Groupings

Use parenthesis to group things together...think complex children

> div>(form>input:text+input:text+input:submit)+p -> div with two children a form (with two inputs and a submit button) and a p tag

### Custom Attribute

Set custom attributes with brackets '[]'

> p[title="Hello world"] -> p with title attribute set to 'Hello world'

### Text

Set inner text for text elements with curly braces '{}'

> p{hello} -> p with inner text of hello

> a{Click here} -> anchor tag with inner text of Click here

### Good to know

Here's some extra ones to know!

> !

> link:css

> script:src

> input:text|email|password|date|number|submit|button

> btn
