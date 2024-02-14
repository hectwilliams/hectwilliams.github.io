Locate docs/build/html/index.html and replace the following keywords:
*   "_static" with "static"
*   "_images" with "images"

Create symbolic links in docs/build/html directory 
*   ln -s /docs/build/html/images  /docs/build/html/_images 
*   ln -s /docs/build/html/static  /docs/build/html/_static  