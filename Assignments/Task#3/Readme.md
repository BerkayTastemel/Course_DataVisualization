### Important Rules
- **No AI Tools:** The use of AI assistants (ChatGPT, Copilot, Gemini, Claude, etc.) is strictly prohibited.
- **Allowed Resources:** You may use the course slides, official R documentation, and the [R Graph Gallery (Violin Plot section)](https://r-graph-gallery.com/violin.html).
- **Academic Integrity:** Write your own code. All submissions will be checked for authenticity.

---

### 1. Data Setup
Run this code in R to prepare your environment. We will use the built-in `iris` dataset; no external downloads or filtering are required.

```r
library(ggplot2)

# Load and inspect the dataset
data(iris)
head(iris)
```

---

### 2. Instructions
As discussed in class, box plots cannot show bimodal (multi-peak) distributions, making **violin plots** a powerful alternative for visualizing distributions across groups. While the theoretical concepts were covered in class, the R implementation was left for you to explore via community documentation.

Using `ggplot2` and referencing the **[R Graph Gallery - Violin Plot](https://r-graph-gallery.com/violin.html)** guide:

1. Create a violin plot showing the distribution of `Sepal.Length` across different `Species`.
2. Map `Species` to the fill color aesthetic so that each group has a distinct fill color.
3. Add appropriate axis labels and a clear title to the plot using.
4. Apply a clean theme.

---

### 3. Submission Steps
- Save your final plot as a `.png` file using `ggsave()`:
  ```r
  ggsave("firstname_lastname_violin.png", width = 8, height = 5, dpi = 300)
  ```
- Name your plot: `firstname_lastname_task3.png`
- Commit both your R script and the `.png` file to your branch.
- Open a Pull Request to this repository with your **Full Name** and **Student ID** in the title.
