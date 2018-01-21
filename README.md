## Install module
  <a name="Install"></a>
   ```
   npm install search-image-google --save
   ```
   
## Require module
  <a name="Require"></a>
   ```javascript
    let sig = require('search-image-google');
  ```

## Syntax
  <a name="Syntax"></a>
  ```
  sig(query, callback(object))
  sig(query, params, callback(object))
  ```
  
## Example
  <a name="Example"></a>
  ```javascript  
  sig('Сats', function(images){
    console.log(images.url, images.filetype, images, width, images.height);
  });
  
  sig('Rain Wallaper', {color: "gray", size: "l"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Banana dance', {filetype: "gif"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Northern Lights', {site: "nasa.gov"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Northern Lights', {site: "gov"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Porn', {size: "l", safe: true}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Tattoo', {size: "l", type: "lineart"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Trump', {size: "l", type: "face"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  
  sig('Jake the dog', {filetype: "gif"}, function(images){
	console.log(images.url, images.filetype, images, width, images.height);
  }
  ```
  
## Documentation
  <a name="Documentation"></a>
  1. [Install](#Install)
  1. [Require](#Require)
  1. [Syntax](#Syntax)
  1. [Example](#Example)
  1. [Colors](#Colors)
  1. [Sizes](#Sizes)
  1. [Types](#Types)
  1. [Time](#Time)
  1. [License](#License)
  1. [Filetype](#Filetype)
  1. [Countries](#Countries)
  1. [Site](#Site)
  1. [Safe](#Safe)

## Colors
  <a name="Colors"></a>
  ```javascript  
  sig('cats', { color: "color"}, function(images){
    console.log(images);
  });

  sig('cats', { color: "gray"}, function(images){
    console.log(images);
  });

  sig('cats', { color: "trans"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## Sizes
  <a name="Sizes"></a>
  ```javascript  
  sig('cats', { size: "l"}, function(images){
    console.log(images);
  });

  sig('cats', { size: "m"}, function(images){
    console.log(images);
  });

  sig('cats', { size: "i"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## Types
  <a name="Types"></a>
  ```javascript  
  sig('cats', { type: "face"}, function(images){
    console.log(images);
  });

  sig('cats', { type: "photo"}, function(images){
    console.log(images);
  });

  sig('cats', { type: "clipart"}, function(images){
    console.log(images);
  });
  
  sig('cats', { type: "lineart"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## Time
  <a name="Time"></a>
  ```javascript
  sig('cats', { time: "d"}, function(images){
    console.log(images);
  });

  sig('cats', { time: "w"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## License
  <a name="License"></a>
  ```javascript  
  sig('cats', { license: "fmc"}, function(images){
    console.log(images);
  });

  sig('cats', { license: "fc"}, function(images){
    console.log(images);
  });
  
  sig('cats', { license: "fm"}, function(images){
    console.log(images);
  });
  
  sig('cats', { license: "f"}, function(images){
    console.log(images);
  });
  ```
  
  ## Filtetype
  <a name="Filtetype"></a>
  ```javascript  
  sig('cats', { filetype: "jpg"}, function(images){
    console.log(images);
  });

  sig('cats', { filetype: "gif"}, function(images){
    console.log(images);
  });
  
  sig('cats', { filetype: "png"}, function(images){
    console.log(images);
  });
  
  sig('cats', { filetype: "bmp"}, function(images){
    console.log(images);
  });
  
   sig('cats', { filetype: "svg"}, function(images){
    console.log(images);
  });
  
   sig('cats', { filetype: "webp"}, function(images){
    console.log(images);
  });
  
   sig('cats', { filetype: "ico"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
  ## Countries
  <a name="Countries"></a>
  See Alpha-2 on <a href="http://www.nationsonline.org/oneworld/country_code_list.htm">Country ISO Codes</a>
  ```javascript  
  sig('cats', { country: "FR"}, function(images){
    console.log(images);
  });

  sig('cats', { license: "AU"}, function(images){
    console.log(images);
  });
  
  sig('cats', { license: "DE"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## Site
  <a name="Site"></a>
  ```javascript  
  sig('cats', { site: ".gov"}, function(images){
    console.log(images);
  });

  sig('cats', { site: "nasa.gov"}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
## Safe
  <a name="Safe"></a>
  ```javascript  
  sig('cats', { safe: true}, function(images){
    console.log(images);
  });
  ```
  **[⬆ back to top](#Install)**
  
