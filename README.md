## Responsive Design Elements in Tailwind CSS

| **Class**               | **Description**                                | **Effect on Different Screen Sizes**       |
|-------------------------|------------------------------------------------|-------------------------------------------|
| `md:flex-row`            | Makes the elements align **horizontally** instead of vertically | Applies **on medium (`md`) screens and larger** |
| `md:w-1/2`               | Makes the element take up **half the width**  | Applies **on medium (`md`) screens and larger** |
| `lg:w-1/3`               | Makes the element take up **one-third of the width** | Applies **on large (`lg`) screens and larger** |
| `md:grid-cols-2`         | Sets the grid to have **2 columns**           | Applies **on medium (`md`) screens and larger** |
| `lg:grid-cols-3`         | Sets the grid to have **3 columns**           | Applies **on large (`lg`) screens and larger** |

### 💡 How does Responsive Design work in Tailwind?

1. **Without any prefix (Base Class):** The style applies to all screen sizes.
2. **When adding `md:` or `lg:`** The property is only applied once the screen reaches the specified size.
