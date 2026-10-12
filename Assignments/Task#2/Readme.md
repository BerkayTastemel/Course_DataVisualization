## ⚠️ Important Rules

- **No AI Tools:** The use of AI assistants (ChatGPT, Copilot, Gemini, Claude, etc.) is strictly prohibited.
- **Allowed Resources:** You may use the course slides, lecture notes, official documentation, and the R scripts from class.
- **Academic Integrity:** Write your own code.

---

## 1. Data Setup

Run this code in R to create the dataset. No data manipulation or extra filtering is needed.

```r
library(ggplot2)

sales_data <- data.frame(
  category = c(
    "Computer Components", 
    "Smartphones & Tablets", 
    "Pet Care Supplies", 
    "Personal Care & Beauty", 
    "Office Supplies & Stationery", 
    "Sports Equipment"
  ),
  units_sold = c(120, 450, 85, 310, 60, 190)
)
```

2. Instructions
Create a bar plot for sales_data using ggplot2. Address the key visualization problems discussed in class

3. Submission Steps
- Save your final plot as a .png file using ggsave():
```r
ggsave("improved_bar_plot.png", width = 8, height = 5, dpi = 300)
```

- Name your file: firstname_lastname_plot.png (e.g., john_doe_plot.png).

- Commit your .png file and your R script to your branch.

- Open a Pull Request to this repository with your name and student ID in the title.
