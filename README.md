# gridx
grid all allowed component

# regulation
0: system signature the ```gridx```
```js
 var gridx={}; ///
```
1: always data serialize the ```dataset```. 
```js
//serialize the .xyz
 let d=document.querySelector('.xyz')
 let se=JSON.stringify(d.dataset)
 save(se)
```
2: always component type the ```dataset.type```.
```js
//type check the coA
 let coA=document.querySelector('.coA')
 if(coA.dataset.type==='imageA') ....
```
3: always component the clouser.
```js
//component clouser template

;(function(root){
 
 function entry(){
  ...
 }
 
 root.coA=entry;
})(gridx);
```
