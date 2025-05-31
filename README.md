# Thesis-Template
This is a repo for Trent University University students that want to write, and require a template to get started. The template is built using [Quarto](https://quarto.org/) and designed for generating PDF output with custom styling and IEEE citation formatting using the [Trent University's 2025 Graduate Thesis and Dissertations Formatting Guidelines](https://www.trentu.ca/graduatestudies/sites/trentu.ca.graduatestudies/files/documents/Thesis%20formatting%20guidelines_FINAL_2025.pdf) .

## 📁 Repository Structure

* `thesis.qmd` – Main Quarto document for writing your thesis.
* `custom_heading.tex` – Custom LaTeX header that modifies the fonts and design of section headings in the final PDF.
* `ieee.csl` – Citation Style Language file for formatting references in the IEEE style.
* `references.bib` – BibTeX file where you can store all your reference entries used in the thesis.

## 🛠 Features

* **Custom Heading Design**: The `custom_heading.tex` file allows you to easily adjust the appearance of your headings using LaTeX styling commands.
* **IEEE Citations**: All in-text citations and references are automatically formatted using the IEEE style via the `ieee.csl` file.
* **BibTeX Integration**: Reference management is handled through `references.bib`, making it easy to cite and update your bibliography.

## 🚀 Getting Started

1. **Install Quarto**:
   [Follow installation instructions here](https://quarto.org/docs/get-started/).

2. **Install LaTeX**:
   Ensure you have a full LaTeX distribution installed (e.g., [TinyTeX](https://yihui.org/tinytex/) or TeX Live).

3. **Render the PDF**:
   Run the following command in your terminal:

   ```bash
   quarto render thesis.qmd --to pdf
   ```

## 💡 Alternative: Using RStudio

If you prefer a graphical interface, you can use [RStudio](https://posit.co/download/rstudio-desktop/) with Quarto:

1. Install RStudio (latest version).
2. Install [Quarto CLI](https://quarto.org/docs/get-started/).
3. Open `thesis.qmd` in RStudio.
4. Use the **Render** button at the top of the editor to compile the PDF.

Make sure LaTeX is installed as noted above.

## 🧾 Example Citation

Inside your `.qmd` file, you can cite a reference using the `@citekey` format (where `citekey` corresponds to an entry in `references.bib`), e.g.:

```markdown
According to recent studies @smith2020, ...
```

## 📝 Customization

To modify the heading styles or typography:

* Edit the `custom_heading.tex` file to define or override LaTeX commands related to fonts and section formats.

## 📄 License

This template is released under the MIT License. Feel free to use and adapt it for your own thesis or academic writing projects.
