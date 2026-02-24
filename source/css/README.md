# Framingham Theme

These SCSS files were adapted from the PreTeXt default-modern theme. Changes include adjusting the default colors to match the Framingham State style guide and making external hyperlinks blue.

## How to Use

1. Extract the css folder and contents to your project's source folder.
2. In your publication.ptx file:
    1. Set `/css/@theme` to `"custom"` in your publication.ptx file.
    2. Enter new argument `/css/@entry-point` and set to `"./css/theme-framingham.scss"`.
    3. Optional: remove other `css` options.
    4. Update any `toc` tags to `tableofcontents`.
3. Run 'pretext build web'.