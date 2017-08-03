# Github Flavored Markdown Syntax Simple Guide

---

## Comments
> You can add comment to markdown by three ways like below:

**Syntax One:**
``` markdown
[comment]: <> (This is a comment, it will not be included)
[comment]: <> (in the output file unless you use it in)
[comment]: <> (a reference style link.)
```

**Syntax Two:**
``` markdown
[//]: <> (This is also a comment.)
```

**Syntax Three: _(Recommend)_**
``` markdown
[//]: # (This may be the most platform independent comment)
```
neither
``` markdown
[//]: # "This may be the most platform independent comment"
```

---

## Horizontal lines
> A line consisting of 0-3 spaces of indentation, followed by a sequence of three or more matching -, _, or * characters, each followed optionally by any number of spaces.

**Syntax:**
``` markdown
***
---
___
```

---

## Headings
> There are six headings just like html tag h1-h6.

- # Heading 1
  `# this is heading 1`

- ## Heading 2
  `## this is heading 2`

- ### Heading 3
  `### this is heading 3`

- #### Heading 4
  `#### this is heading 4`

- ##### Heading 5
  `##### this is heading 5`

- ###### Heading 6
  `###### this is heading 6`

---

## Code highlight
> Print code and highlight code syntax.

- single line code:  `console.log('hi there').`

- multi lines code:

  - javascript code:

    ``` javascript
    // class of dog
    export default class Dog {
      constructor(name) {
        this.name = name;
      }
      bark() {
        console.log('Wun, wun, wun...');
      }
    }
    ```

  - Ruby code:

    ``` ruby
    def foo(x)
      return 3
    end
    ```

---






[//]: # "Some pre defined links here"
[homepage]: https://armdong.github.io/markdown-101/
