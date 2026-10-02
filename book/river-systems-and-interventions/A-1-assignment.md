# Chapter Title (Syntax Chapter
text

## Section Title 1


## Section Title 2
text

### Subsection Title 1
text

### Subsection Title 2
text

#### Heading
##### Smaller Heading
###### Figure Example:
```{figure} figures/book layout.pdf
---
width: 80%
align: center
---
<Book layout>
```
###### Audio from file in repository: 
<audio controls>
  <source src="audio/7conclusions.mp4" type="audio/mp4">
  Your browser does not support the audio element.
</audio>

## Video from file in repository: 
<video controls width="80%">
  <source src="audio/mp4test.mp4" type="video/mp4">
  Your browser does not support HTML video.
</video>

###### Video from Youtube:
```{video} https://www.youtube.com/watch/B1J6Ou4q8vE
```

###### Equation examples:
$$ F_(res) = m \cdot a $$
$$ E = m \cdot c^2 $$

```{math}
v = a \cdot t
```

###### Table examples: 
| Column 1 | Column 2 | Column 3 |
|---|---|---|
| Data 1  | Data 2  | Data 3  |
| Data 4  | Data 5  | Data 6  |

```{table} Table caption
:widths: auto
:align: center

| Header 1      | Header 2      | Header 3      |
|---------------|---------------|---------------|
| Row 1, Col 1  | Row 1, Col 2  | Row 1, Col 3  |
| Row 2, Col 1  | Row 2, Col 2  | Row 2, Col 3  |
```

```{list-table} Sample Data Table
:header-rows: 1
* - Category
  - Value 1
  - Value 2
* - Item A
  - 10
  - 20
* - Item B
  - 15
  - 30
''''
