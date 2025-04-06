# Typst Template for VSCode

Simple template for Typst with VSCode.

Notes:
- [typstyle](https://github.com/Enter-tainer/typstyle) is used to lint and format the code
- CI is already set up to build and upload PDFs, as long as the main `.typ` files exist in the root folder, with the ability to create tagged releases.
- The local settings disable the system fonts, and add the `fonts` folder to the font path to improve reproducibility.
