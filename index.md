---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

```SPARQL
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX arco: <https://w3id.org/arco/ontology/arco/>
SELECT COUNT(DISTINCT ?clothing) AS ?n
WHERE { 
?clothing rdfs:label ?label ; 
                a arco:HistoricOrArtisticProperty ;
                a-dd:hasIconographicOrDecorativeApparatus ?dec .
FILTER(REGEX(?label,  "da cocktail", "i"))
}
```
1
![abitocorto_paillettes](/immagini_markdown/abitocorto_paillettes.jpg)

2.5
<img src="/immagini_markdown/abitocorto_paillettes.jpg" alt="Pet Sematary book cover" style="width:200px;height:250px;" style="float:left;margin: 10px" width="250"/>

2
<img src="https://www.sigecweb.beniculturali.it/images/fullsize/ICCD1070166/ICCD15928135_FTMUBOL46.jpg" alt="abito paillettes" style="float:left;margin: 10px" width="250"/> abito corto da cocktail in seta nera completamente ricoperto di paillettes color bronzo. L'abito è formato da una gonna dritta unita a un corpino aderente dall'ampio décolleté sostenuto a 2 bretelle. Sulla gonna, all'altezza del punto vita, è cucita una piega laterale fermata da un grande fiocco ricoperto di paillettes viola e poi lasciata sciolta
#

hello

3
<img src="/immagini_markdown/abitocorto_paillettes.jpg" alt="abito paillettes" width="400"/>

4
![abito corto con paillettes](https://www.sigecweb.beniculturali.it/images/fullsize/ICCD1070166/ICCD15928135_FTMUBOL46.jpg)

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
