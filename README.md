- [1. Typography](#Typography)
- [2. Layout and Grill](#Layout-and-Grill)
- [3. Table layout](#Table-layout)
- [4. Colors variables and Theme](#Colors-variables-and-Theme)
- [5. UI component](#UI=component)
- [6. Icons & Illustrations](#Icons-&-Illustrations)
- [7. Animation](#Animation)
- [8. Style Naming convention](#Style-Naming-convention)
- [9. Function Naming convention](#Function-Naming-convention)



# Typography
Font-size should be set by REM unit.
Using the "rem" unit allows for a more scalable and flexible way to size elements on a page because if you change the font-size of the root element, all elements sized with the "rem" unit will be updated automatically to maintain their relative size.
Accessibility: Rem units are particularly beneficial for users who adjust their browser settings for larger text, as these units scale according to user-defined preferences

```
html, body {
  font-size : 16px;
}

button {
  font-size : 1rem;
}

```

## Header


```
<h1>header</h1>
<h2>header</h2>

h1 {
  font-size : 2.5rem;
}

h2 {
  font-size : 2rem;
}

```


## Color and size
| Type     | Couleur Bootstrap | Couleur Material UI |
|----------|------------------|--------------------|
| Succès   | `#198754`        | `#4CAF50`         |
| Danger   | `#dc3545`        | `#F44336`         |
| Avertissement | `#ffc107`    | `#FF9800`         |
| Info     | `#0dcaf0`        | `#2196F3`         |

# Layout and Grill
## Grill and Container
| Type of container | behavior |
|------------------|-------------|
| `.container` | fixe width adapte to breakpoints |
| `.container-sm` | 100% width to  `sm` (`≥576px`), puis largeur fixe |
| `.container-md` | 100% width to  `md` (`≥768px`), puis largeur fixe |
| `.container-lg` | 100% width to  `lg` (`≥992px`), puis largeur fixe |
| `.container-xl` | 100% width to  `xl` (`≥1200px`), puis largeur fixe |
| `.container-xxl` | 100% width to  `xxl` (`≥1400px`), puis largeur fixe |
| `.container-fluid` | 100% on all screen |

## Breaking Points
| Type      | Class label | width |
|----------|---------|----------------|
| Extra Small | `xs` (par défaut) | `<576px` |
| Small | `sm` | `≥576px` |
| Medium | `md` | `≥768px` |
| Large | `lg` | `≥992px` |
| Extra Large | `xl` | `≥1200px` |
| Extra Extra Large | `xxl` | `≥1400px` |
## Marging & Padding on mobile device

| Container      | attribut | value |
|----------|---------|----------------|
| Background |  padding | 1rem (16px) |
| frame | padding | 2rem 1.25rem 1.5rem |
| frame | margin-bottom | 1.5rem (24px) |

## Button on mobile device
```
.btn-sm {
    --bs-btn-padding-y: 0.25rem;
    --bs-btn-padding-x: 0.5rem;
    --bs-btn-font-size: 0.875rem;
    --bs-btn-border-radius: 0.25rem;
}
```

# Colors variables and Theme

## Input
```
input { 
    font: 1em sans-serif;
    padding: 0.625rem;
    border-radius: 0.25rem;
    background-color: #52667D;
    color: #cecece;
    border: none;
}

input:disabled { 
    font: 1em sans-serif;
    padding: 0.625rem;
    border-radius: 0.25rem;
    background-color: #52667D;
    color: #A8A8A8;
    border: none;
}
```
# Icons & Illustrations
https://icons.getbootstrap.com/
[Icons from Bootstrap](https://icons.getbootstrap.com/)

# Animation

# Style Naming convention
## Summary of SMACSS Rules
[The guide of SMACSS](https://smacss.com/)

| Category  | Purpose  | Naming Convention  | Example  |
|-----------|---------|-------------------|---------|
| **Base** | Global styles (reset, typography) | Use element selectors | `body { margin: 0; }` |
| **Layout** | Structural elements (grid, header) | Prefix with `l-` | `.l-container { width: 90%; }` |
| **Modules** | Reusable components (buttons, cards) | Tag Prefix | `.button-primary {}` |
| **State** | Temporary states (active, hidden) | Prefix with `is-` or `has-` | `.is-active {}` |
| **Theme** | Style variations (light/dark mode) | Prefix with `theme-` | `.theme-dark {}` |



# Typescript Naming convention
[Typescript coding convention](https://smacss.com/)

```
function allo() {
let message =  "hello world";
console.log(message);
}
```

```
.btn-add-user {

border: 1px solid #c1c1c1;
color: #fff;

} 

```



<!---
sderaspeCC/sderaspeCC is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
