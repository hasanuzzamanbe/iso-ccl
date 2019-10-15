# iso-ccl (Country, Currency, Language)
Easy way to use all the iso countries, currencies and languages with npm.

## Usages
Install the latest version:

```npm i iso-ccl```

Require the module in your code & start using:

```const {country, currency, language, countryCodes} = require('iso-ccl');```

#Documentation
####Single import of country

`const {country} = require('iso-ccl');`

then just use `country` anywhere of the imported js file.

data formate of ``country`` is as like bellow:

``` 
   {  
     code: 'US', 
     name: 'United States'
   }
 ```
   
#### Single import of Currency

`const {currency} = require('iso-ccl');`

then just use `currency` anywhere of the imported js file.

data formate of ``currency`` is as like bellow:
          
         {
           "symbol": "$",
           "name": "US Dollar",
           "symbol_native": "$",
           "decimal_digits": 2,
           "rounding": 0,
           "code": "USD",
           "name_plural": "US dollars"     
        }
        


#### Single import of country with phone code

`const {countryCodes} = require('iso-ccl');`

then just use `countryCodes` anywhere of the imported js file.

data formate of ``countryCodes`` is as like bellow:

```
 {
   'name': 'ANDORRA', 
   'code': '376'
 }
```

#### Single import of language
`const {language} = require('iso-ccl');`

then just use `language` anywhere of the imported js file.
   
data formate of ``language`` is as like bellow:

```
   {
     code: 'ab', 
     name: 'Abkhazian'
   }
   ```

## supports:
Thanks for using this package, If you have any query or suggestion please let me know about it.

<a href="mailto:hasanuzzamanbe@gmail.com?Subject=npm-ccl%20issue" target="_top">Send Mail</a>
