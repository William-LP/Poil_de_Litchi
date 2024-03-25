# URL
https://william-lp.github.io/Poil_de_Litchi/

# To do
* Contact form
* Create backend to manage images
* Load [full_size](img/full_size)'s image AFTER webpage has been loaded

# Image Processing
* Set lowest side's value (x / y) to 310 px 
* Keep natural ratio
* Copy modified file to [preview](img/preview) folder.
* Keep original file within [full_size](img/full_size) folder.

# db.json
Get list using JQ
```bash 
cat db.json | jq -r '.images[] | .title'
```
