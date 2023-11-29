# Siamak Faal's CV

Welcome to the GitHub repository containing my curriculum vitae (CV).

## Repository Structure

- `CV.md`: This is the main file, containing my CV in Markdown format.
- `CV.pdf`: A PDF version of my CV, auto-generated from `CV.md`.
- `CV.docx`: A Word document version of my CV, auto-generated from `CV.md`.

## Automatic Conversion

This repository is configured with GitHub Actions to automatically convert the `CV.md` file into PDF and DOCX formats every time an update is made to the file. This ensures that the most recent version of my CV is always available in all three formats.

### How it Works

- **On every push to the repository**, the GitHub Actions workflow is triggered.
- **The workflow** runs a script that uses Pandoc to convert `CV.md` to `CV.pdf` and `CV.docx`.
- **The generated files** are then automatically committed back to the repository.

## Editing the CV

To update the CV:

1. Clone the repository to your local machine.
2. Make your changes to `CV.md`.
3. Commit and push these changes back to the repository.
4. The GitHub Actions workflow will take care of the rest, automatically updating `CV.pdf` and `CV.docx`.

## Feedback

If you have any suggestions or feedback, please feel free to create an issue in this repository.
