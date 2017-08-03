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

## Link
> Square brackets shows link text and parentheses define the link url.

**Syntax:**
``` markdown
[link_text](link_url)
[link_text](link_url "link_title")

[link_text][link_id]
[link_id]: link_url "link_title"
```

**Usage:**
- This is the link to [Google](http://www.google.com).
- This is the link to [Baidu](https://www.baidu.com "Baidu").
- This is the link to [Github][github].
- This is the link to [Twitter][twitter].

---

## Image

**Syntax:**
``` markdown
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![Alt text][id]
[id]: url/to/image "Optional title attribute"
```

**Usage:**

![Dinotocat Image](https://octodex.github.com/images/dinotocat.png)

![Inflatocat Image](https://octodex.github.com/images/inflatocat.png "this is the inflatocat image")

![Privateinvestocat Image][privateinverstocat]

---

## Image Link

**Syntax:**
``` markdown
[![Alt text](/path/to/img.jpg "Optional image title")](link_url "Optional link title")
```

**Usage:**
Click the page and redirct to my Github. [![Github Image](https://octodex.github.com/images/saritocat.png "Saritocat")](https://github.com/armdong)

---

## Bold and Italic




[//]: # "Some pre defined links here"
[homepage]: https://armdong.github.io/markdown-101/
[github]: https://github.com
[twitter]: https://twitter.com "Twritter Homapage"
[privateinverstocat]: https://octodex.github.com/images/privateinvestocat.jpg "This is the private investocat image"
