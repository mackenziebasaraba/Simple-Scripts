For more information on each script visit [my website](https://www.mackenziebasaraba.ca/programs/simple-scripts/)

**batch-convert-images**

Utilizes ImageMagick to batch convert images to a specific format, quality and size. If an input directory/file isn't specified it will continue to process all images in child directories.

Arguments
- [output_format] :: The format to convert to (e.g. jpg, png, avif, webp).
- -r --resize :: Resize dimensions (e.g., 800x800, 800x, x800, or 50%) [optional].
- -q --quality :: Quality settings (e.g., 90 or lossless) [optional].
- -i --input :: The sole image/directory this script targets. [optional] 

**bookmark**

A simple script to add and utilize bookmarks through dmenu.

Arguments
- -d, --display :: Display a list of saved bookmarks.
- -a, --add    :: Log the URL stored in the clipboard; configure title and tags.

**consolidate**

Merges all Biber files into a master file which can then be called by LaTeX. I have this automatically run when I save a bib file with Vim.
