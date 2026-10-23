Put square (1:1) ad images in this folder, named with numbers in order:

  1.png
  2.gif
  3.jpg
  ...

Each number can be .png, .gif, or .jpg (gifs animate).

The home page shows them one at a time in the left column, switching every
few seconds. It stops looking at the first missing number, so don't skip any
(if you have 1.png and 3.png but no 2, only 1.png will show).

To allow another file type (like .webp), or change how long each ad shows,
edit adTypes and adSeconds in the <script> at the bottom of index.html.

If this folder has no 1.png, the Ad card stays hidden.
