# GitHub Basics for Academic Researchers

A comprehensive beginner's guide to using GitHub for academic projects, research collaboration, and open science.

## About This Book

This tutorial teaches academics how to use GitHub effectively for their research projects. It covers everything from creating your first GitHub account to managing complex collaborative projects.

## What You'll Learn

- How to create and set up a GitHub account
- Personal Access Tokens (PAT) for secure authentication
- Essential Git commands for daily use
- Complete GitHub workflow for academic projects
- Best practices for research collaboration
- Repository management and organization

## Prerequisites

- A computer with internet connection
- An email address
- 30 minutes of focused time
- No prior programming experience required

## Building the Book

This book is built with [bookdown](https://bookdown.org/). To build it locally:

### Option 1: Using R/RStudio

```r
# Install required packages
install.packages(c("bookdown", "rmarkdown"))

# Build the book
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

### Option 2: Using Command Line

```bash
# Ensure you have R and required packages installed
Rscript -e "bookdown::render_book('index.Rmd', 'bookdown::gitbook')"
```

The book will be generated in the `_book/` directory.

## Book Structure

- `index.Rmd` - Welcome page and introduction
- `01-github-signup.Rmd` - Creating your GitHub account
- `02-personal-access-tokens.Rmd` - Setting up secure authentication
- `03-essential-git-commands.Rmd` - Learning Git basics
- `04-github-workflow.Rmd` - Complete workflow for academic projects

## Contributing

This book is designed to be a living resource. If you find errors, have suggestions for improvements, or want to contribute new content:

1. Fork this repository
2. Make your changes
3. Submit a pull request

## License

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

## Target Audience

This tutorial is specifically designed for:
- Graduate students starting their research
- Faculty new to version control
- Research teams wanting to collaborate better
- Anyone in academia interested in open science practices

## Feedback

Have questions or suggestions? Please:
- Open an issue in this repository
- Email the author
- Discuss in the academic GitHub community

## Author

[Your Name]  
[Your Institution]  
[Your Email]

---

*Happy coding and collaborating!* 🚀 