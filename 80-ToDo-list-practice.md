# Practice

```
var toDoList = [

    {id: 1, name: "take a shower", status: false},
    {id: 2, name: "brush my these", status: true},
    {id: 3, name: "have a breakfast", status: false},

]



console.log(toDoList)

var showAllList = toDoList.some(function(item) {
    console.log(item)
})



var chooseOperation = prompt("1. Change status of your items \n2. Add item \n3. Delete item")

// console.log(chooseOperation)

if (chooseOperation == "1") {

    var itemName = prompt("Please enter your item name")

    var isInList = toDoList.some(function(item) {

        return item.name == itemName
    
    })

    // console.log(isInList)


    if (isInList) {

        var findItem = toDoList.findIndex(function(item) {

            if (item.name == itemName){

                // console.log(item)
                return item

            }

        })
        // console.log(findItem)


        var statusChange = prompt("If you want to change status of your item please choose \n1. Did it \n2. Did not it")

        // console.log(statusChange)



        if (statusChange == "1") {

            toDoList.map(function(item) {

                if (item.name == toDoList[findItem].name) {
                        
                    toDoList.splice(findItem, 1, {
                        
                        id: item.id, 
                        name: item.name, 
                        status: true,
                    
                    })
        
                }
        
            })

        } else if (statusChange == "2") {

            toDoList.map(function(item) {

                if (item.name == toDoList[findItem].name) {
                        
                    toDoList.splice(findItem, 1, {
                        
                        id: item.id,
                        name: item.name,
                        status: false,
                    
                    })
        
                }
        
            })

        }

        console.log(toDoList)

    } else {

        console.log("We don't have this item")

    }


} else if (chooseOperation == "2") {

    var itemName = prompt("Please enter your item name")
    var itemStatus = prompt("Please enter your item status \n1. true \n2. false")

    if (itemStatus == "1") {

        toDoList.push({

            id: toDoList.length+1,
            name: itemName,
            status: true,
    
        })

    } else if (itemStatus == "2") {

        toDoList.push({

            id: toDoList.length+1,
            name: itemName,
            status: false,
    
        })

    } else {

        console.log("We don't have this item")

    }

    console.log(toDoList)

} else if (chooseOperation == "3") {

    var itemName = prompt("Please enter your item name")

    var findItem = toDoList.findIndex(function(item) {

        if (item.name == itemName){

            // console.log(item)
            return item

        }

    })
    // console.log(findItem)


    toDoList.splice(findItem, 1)


    console.log(toDoList)

} else {

    console.log("We don't have this item")

}
```