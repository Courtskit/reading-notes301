# Responsive Web Design 

## **RWD** - *Responsive Web Design*

1. Responsive
2. Adaptive
3. Mobile

- % or em 
- vw and vh

target / context = result

### Media Queries
`@media `
- arrange the layout based on screen sizes 

- logical operators include: and, not, and only

- landscape or portrait orientation

- viewport scale

- flexible media > max-width:100%


---

## Float

positions elements to left or right of containing element, taking it out of normal document flow

parent element can collapse *"the great collapse"*


Clear left, right, or both

- ex.) clear: both

Clear a classes floats
.class:after{
  content: "";
  display: block;
  clear: both;
}

---

## Grids

#### Columns

```
HTML:
<div class="grid">
  <div class="col-2-3">
     Main Content
  </div>
  <div class="col-1-3">
     Sidebar
  </div>
</div>

CSS:
[class*='col-'] {
  float: left;
}

.col-2-3 {
  width: 66.66%;
}
.col-1-3 {
  width: 33.33%;
}

//Clearing Context

.grid:after {
  content: "";
  display: table;
  clear: both;
}
```
---
```
display:grid;

grid-template-columns: 33.3% 33.3% 33.3%;
OR
grid-template-columns: 1fr 1fr  1fr;
OR
grid-template-columns: repeat(3, 1fr);
```

#### Gutters | Outside Gutters
Gutters:
`box-sizing: border-box;`
`padding-right: .2%;`

Outside Gutters can be easily fixed with padding

---
## Scalable and Modular Architecture for CSS
### *SMACSS* - style guide for your CSS


5 categories:
- Base
- Layout
- Module
- State
- Theme

