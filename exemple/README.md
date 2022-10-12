 

                                1 examp
```js
function getVoteCount(obj){
    return(obj.upvotes - obj.downvotes)
}
console.log(getVoteCount({ upvotes: 13, downvotes: 0 }))


function getVoteCount(Sos){
    return(Sos.upvotes - Sos.downvotes)
}
console.log(getVoteCount({ upvotes: 2, downvotes: 33 }) )

function getVoteCount(coc){
    return(coc.upvotes - coc.downvotes)
}
console.log(getVoteCount({ upvotes: 132, downvotes: 132 }))
```


```js
        Volume of a Box
```
           2 exemp
```js
function volumeOfBox(obj){
    return(obj.width * obj.length * obj.height);
}
console.log(volumeOfBox({ width: 2, length: 5, height: 1 }) )
   
   volumeOfBox({ width: 2, length: 5, height: 1 })
 ```

```js
function volumeOfBox(obj){
    return(obj.width * obj.length * obj.height);
}
console.log(volumeOfBox({ width: 4, length: 2, height: 2 }) )

volumeOfBox({ width: 4, length: 2, height: 2 })
```


```js
function volumeOfBox(obj){
    return(obj.width * obj.length * obj.height);
}
console.log(volumeOfBox({ width: 2, length: 3, height: 5 }) )

volumeOfBox({ width: 2, length: 3, height: 5 }) 
```

                 3 exemp
```js
 function fiftyThirtyTwenty(obj){
    return(obj.Needs + obj.Wants + obj.Savings)
}
console.log(fiftyThirtyTwenty({ "Needs": 5000, "Wants": 3000, "Savings": 2000 }))

function fiftyThirtyTwenty(obj){
    return(obj.Needs + obj.Wants  + obj.Savings)
}
console.log(fiftyThirtyTwenty({ "Needs": 25000, "Wants": 15000, "Savings": 10000 }))

function fiftyThirtyTwenty(obj){
    return(obj.Needs + obj.Wants + obj.Savings)
}
console.log(fiftyThirtyTwenty({ "Needs": 6725, "Wants": 4035, "Savings": 2690 }))

```
```s
 fiftyThirtyTwenty(10000) ➞ { "Needs": 5000, "Wants": 3000, "Savings": 2000 }

 fiftyThirtyTwenty(50000) ➞ { "Needs": 25000, "Wants": 15000, "Savings": 10000 }

 fiftyThirtyTwenty(13450) ➞ { "Needs": 6725, "Wants": 4035, "Savings": 2690 }

```////////////////////////////////////////////


                      ecemp 4

```js
 let cityFacts={
    name: "Paris",
    population: "2,140,526",
    continent: "Europe"
}
console.log(cityFacts.name + " has a population of " + cityFacts.population + " and is situated in "  + cityFacts.continent )

/// ➞ "Paris has a population of 2,140,526 and is situated in Europe"
  


   let cityFacts1 = { 
     name: "Tokyo",
     population: "13,929,286",
     continent: "Asia"

   } 
  console.log( cityFacts1.name + " has a population of " + cityFacts1.population + " and is situated in " + cityFacts1.continent)
//  

//➞ "Tokyo has a population of 13,929,286 and is situated in Asia"
``` 
////////////////////////////////////////
             exemple 5


```s
let arr = [1, 2, 3, 4, 5, 6, 7, 8];
let first = arr[0];
let second = arr[1];
let third = arr[2];
let other = arr.slice(3);

arr.push('d');

console.log(" outputs " + first); 
console.log(" outputs " + second);
console.log(" outputs " + third); 
console.log(" outputs " + other);
```