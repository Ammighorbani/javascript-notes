# Pracitce

```
var stateList = [

    {id:"tehran", citys: ["tehran", "pardis", "fardis", "karaj"]},
    {id:"karaj", citys: ["mehrshahr", "golshahr", "kamal shahr"]},
    {id:"mazandaran", citys: ["chaloos", "noshahr", "royan", "noor"]},

]

// var showStateList = stateList.forEach(function(state) {

//     console.log(state.id, state.citys)

// })


var stateName = prompt("please enter state name")


var showCitys = stateList.map(function(state) {

    if (state.id === stateName) {

        for (var i = 0; i < state.citys.length; i++) {

            console.log((i+1) + "- " + state.citys[i])
        
        }

    }

})
```