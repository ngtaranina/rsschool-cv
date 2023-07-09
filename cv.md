# Nataliya Taranina
## RS School stage-0
***
## my contact:

### Contact information:
* ___Phone:___ +79995186183
* ___E-mail:___ ngtaranina@gmail.com
* ___Telegram:___ @NG Taranina
***
## About myself:
***
## My skills and proficiency:
***
## Exemple of my code:
### Codwars kata:
_The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value._
```
function rgb(r, g, b){
  arrRGB = [r,g,b];
 let result = '';
  arrRGB.forEach(element => {
    if (element < 0) element = 0;
    if (element > 255) element = 255;
    element = element.toString(16);
    if (element.length < 2) element = '0'+ element;
    result = result + element;
  });
  result = result.toUpperCase()
  console.log(result);
  return(result);
}
```
***
## Languages:
1. ___Russian___ _- native_
2. ___Ukranian___ _- intermediate_
3. ___English___ _- Intermediate_
