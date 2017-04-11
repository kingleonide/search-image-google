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
