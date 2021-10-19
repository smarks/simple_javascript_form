# simple_javascript_form
an html form using javascript to submit json data to your endpoint. 

## created by @katelynnobrien -- thank you Kate!
 
## How to use

Simply replace `'http://apiurl'` with your endopint point (that accpets POSTs) 

If you are really good, you can also hadd sokme error handling :> 
```
  // send json to api
        fetch('http://apiurl', {
          method: 'POST',
          body: json,
          headers: {
            'Content-type': 'application/json; charset=UTF-8'
          }
        }).then(function (response) {
          // do something with the response
        }).catch(function (error) {
          // do something with the error
        });
        
      }
```
