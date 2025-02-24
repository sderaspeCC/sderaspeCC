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

## Header

## paragraphe 

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
## Marging and Padding
## Mobile device

# Table layout
## Header
## Border
## Typoghraphy
## Line odd and even

# Colors variables and Theme

# UI component
## button
## Form and Input

# Icons & Illustrations

# Animation

# Style Naming convention
## Summary of SMACSS Rules

| Category  | Purpose  | Naming Convention  | Example  |
|-----------|---------|-------------------|---------|
| **Base** | Global styles (reset, typography) | Use element selectors | `body { margin: 0; }` |
| **Layout** | Structural elements (grid, header) | Prefix with `l-` | `.l-container { width: 90%; }` |
| **Modules** | Reusable components (buttons, cards) | Use BEM | `.button--primary {}` |
| **State** | Temporary states (active, hidden) | Prefix with `is-` or `has-` | `.is-active {}` |
| **Theme** | Style variations (light/dark mode) | Prefix with `theme-` | `.theme-dark {}` |



# Typescript Naming convention
- [Typescript coding convention](https://google.github.io/styleguide/tsguide.html)


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
