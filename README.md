# Birthday Paradox Simulation

A simple R project to explore the famous Birthday Paradox through simulation and visualization.

## The Question

In a room of N people, what's the probability that at least two people share a birthday?

**Spoiler**: With just 23 people, there's a >50% chance of a shared birthday!

## Project Goals

This project serves two purposes:
1. **Learn git collaboration**: Practice branching, merging, and resolving conflicts
2. **Explore probability**: Use simulation to understand a counterintuitive result

## Files

- `birthday_paradox.Rmd` - Main R Markdown file with simulation and visualizations
- `.gitignore` - Excludes generated files (HTML, cache, etc.)

## Requirements

- R (version 4.0+)
- RStudio (recommended)
- R packages: `ggplot2`, `knitr`, `rmarkdown`

## Usage

1. Open `birthday_paradox.Rmd` in RStudio
2. Install required packages if needed:
   ```r
   install.packages(c("ggplot2", "knitr", "rmarkdown"))
   ```
3. Click "Knit" to generate the HTML report

## Git Workflow

We're using this project to practice:
- Creating feature branches
- Making pull requests
- Resolving merge conflicts
- Code review

### Suggested branches:
- `simulation-functions` - Implement the core simulation logic
- `theoretical-calculations` - Add theoretical probability calculations
- `visualization` - Create plots and charts
- `comparison-plots` - Compare simulation vs theory

## Extensions

Ideas for expanding the project:
- Vary the number of days in a year
- Consider birth months instead of exact dates
- Visualize distributions of matching pairs
- Explore the "almost birthday" problem (birthdays within k days)

## Authors

[Your Names Here]

## License

This is a learning project - feel free to use and modify!
