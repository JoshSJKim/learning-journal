# Learning Journal 

---

## CSS

### Today I learned: Jan 16. 2023

### a: pseudo-class hierarchy

- a:hover MUST come after a:link and a:visited in the CSS definition in order to be effective! a:active MUST come after a:hover in the CSS definition in order to be effective!
  
For example:

     a:link {
      }
     a:visited {
      }
     a:hover {
      }
     a:active {
      } 
      
---
## HTML
      
### Today I learned: Jan. 18. 2023

### How to insert image file locally

When inserting image file to html from a local hard drive, you must use a relative path. 
Using a full path will make the browser attempt to access the file as if it were a URL, but the path is not a valid URL.
So, use a relative path when working locally. 

For example: 

Rather than using a full path, such as

``` <img src="/Users/[username]/[file_path]"> ```

use a relative path as such

``` <img src="./image_file.jpg"> ```

Making sure that the image file is saved in the same folder as the html file. 

### Today I learned: Jan 20, 2023 - FCC certification project2

- READ THE CODE CAREFULLY, even with linter extensions installed.
- Failed to close anchor tags on social icons, which prevented CSS styles from being applied. 
- Spend more time picking at flex box and grid. Position property as well. 
- margin: auto; will center the item horizontally and vertically. 
- object-fit: cover; will ensure the image covers the entire container while maintaining aspect ratio. 
- text-align: center; applied in a div container will also center image files in the container as well.
