## Alexey Potapeiko
***
#### Contacts:
* Discord: @NL4Alex
* E-mail: a.potapeyko (@) gmail.com
* Phone: on request

#### About myself:
I'm a Project Manager (ERP systems implementation) and now I'm studying Frontend development at RS School to switch my career.

#### Code example:
```
function toCamelCase(str){
  let words = [];
  if ( str.includes("-") ) {
    words = str.split("-");
  } else if ( str.includes('_') ) {
    words = str.split('_'); 
  } else { return str; 
  }
    
  for (let i = 1; i < words.length; i++) {
    words[i] = words[i][0].toUpperCase() + words[i].slice(1);
  }
  return words.join('');    
}
```
#### Education:
Bachelor degree in physics in Belarusian State University, Minsk.

#### Language:
English: C1 level
Russian: native