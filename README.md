## Table of Contents
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
  
## Require module
  <a name="Require"></a><a name="1.1"></a>
 ```javascript
  let sig = require('search-image-google');
```

## Colors
  <a name="Colors"></a><a name="1.1"></a>
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
  
## Sizes
  <a name="Sizes"></a><a name="1.1"></a>
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
  
## Time
  <a name="Time"></a><a name="1.1"></a>
  ```javascript  
  sig({search: "cats", type: "d"}, function(images){
    console.log(images);
  });

  sig({search: "cats", type: "w"}, function(images){
    console.log(images);
  });
  ```
  
## License
  <a name="License"></a><a name="1.1"></a>
  ```javascript  
  sig({search: "cats", type: "fmc"}, function(images){
    console.log(images);
  });

  sig({search: "cats", type: "fc"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", type: "fm"}, function(images){
    console.log(images);
  });
  
  sig({search: "cats", type: "f"}, function(images){
    console.log(images);
  });
  ```
  
  ## Filtetype
  <a name="Filtetype"></a><a name="1.1"></a>
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
