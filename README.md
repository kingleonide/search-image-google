## Content
  <a name="Content"></a>
  1. [Install](#Install)
  1. [Require](#Require)
  1. [Colors](#Colors)
  1. [Sizes](#Sizes)
  1. [Types](#Types)
  1. [Time](#Time)
  1. [License](#License)
  1. [Filetype](#Filetype)
  1. [Countries](#Countries)
  1. [Site](#Site)
  1. [Safe](#Safe)
  1. [Example](#Example)
  
## Install module
  <a name="Install"></a>
   ```npm install search-image-google --save
   ```
  
## Require module
  <a name="Require"></a>
   ```javascript
    let sig = require('search-image-google');
  ```
  
## Colors
  <a name="Colors"></a>
  ```javascript  
  sig({search: "cats", color: "color"}, function(images){
    console.log(images);
  });

  sig({search: "cats", color: "gray"}, function(images){
    console.log(images);
  });

  sig({search: "cats", color: "trans"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Sizes
  <a name="Sizes"></a>
  ```javascript  
  sig({search: "cats", size: "l"}, function(images){
    console.log(images);
  });

  sig({search: "cats", size: "m"}, function(images){
    console.log(images);
  });

  sig({search: "cats", size: "i"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Types
  <a name="Types"></a><a name="1.1"></a>
  ```javascript  
  sig({search: "cats", type: "face"}, function(images){
    console.log(images);
  });

  sig({search: "cats", type: "photo"}, function(images){
    console.log(images);
  });

  sig({search: "cats", type: "clipart"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", type: "lineart"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Time
  <a name="Time"></a>
  ```javascript  
  sig({search: "cats", time: "d"}, function(images){
    console.log(images);
  });

  sig({search: "cats", time: "w"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## License
  <a name="License"></a>
  ```javascript  
  sig({search: "cats", license: "fmc"}, function(images){
    console.log(images);
  });

  sig({search: "cats", license: "fc"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", license: "fm"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", license: "f"}, function(images){
    console.log(images);
  });
  ```
  
  ## Filtetype
  <a name="Filtetype"></a>
  ```javascript  
  sig({search: "cats", filetype: "jpg"}, function(images){
    console.log(images);
  });

  sig({search: "cats", filetype: "gif"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", filetype: "png"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", filetype: "bmp"}, function(images){
    console.log(images);
  });
  
   sig({search: "cats", filetype: "svg"}, function(images){
    console.log(images);
  });
  
   sig({search: "cats", filetype: "webp"}, function(images){
    console.log(images);
  });
  
   sig({search: "cats", filetype: "ico"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
  ## Countries
  <a name="Countries"></a>
  See Alpha-2 on <a href="http://www.nationsonline.org/oneworld/country_code_list.htm">Country ISO Codes</a>
  ```javascript  
  sig({search: "cats", country: "FR"}, function(images){
    console.log(images);
  });

  sig({search: "cats", license: "fc"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", license: "fm"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Site
  <a name="Site"></a>
  ```javascript  
  sig({search: "cats", site: ".gov"}, function(images){
    console.log(images);
  });

  sig({search: "cats", site: "nasa.gov"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Safe
  <a name="Safe"></a>
  ```javascript  
  sig({search: "cats", safe: "active"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
  
## Example
  <a name="Example"></a>
  ```javascript  
  sig({search: "cats", safe: "active"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Content)**
