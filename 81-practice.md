# Practice

```
var Employees = [

    {id: 1, name: "amir", position: "boss", tasks: ["managment"]},
    {id: 2, name: "mamad", position: "designer", tasks: ["re-design things"]},
    {id: 3, name: "amin", position: "developer", tasks: ["develop new design"]},
    {id: 4, name: "babak", position: "Purchasing Officer", tasks: ["buy new items"]},
    {id: 5, name: "salar", position: "DevOps", tasks: ["automate things in server"]},

]

var showEmployees = Employees.forEach(function(item) {

    console.log(item)

})


var guyName = prompt("Enter your name")

var isBoss = Employees.some(function(item) {

    if (item.name === guyName && item.position === "boss") {

        return item

    }

})

// console.log(isBoss)



if (isBoss) {

    var employeeName = prompt("Enter name of employee you want")
    
    var isEmployee = Employees.some(function(item) {
    
        if (item.name === employeeName) {
            
            return item
            
        }
        
    })
    
    // console.log(isEmployee)


    if (isEmployee) {

        var task = prompt("Enter task you want")
        
        var addTask = Employees.map(function(item) {
        
            if (item.name === employeeName) {
        
                item.tasks.push(task)
        
            }
        
        })
        
        console.log(Employees)
        
    
    } else {

        console.log("We don't have this employee")

    }


} else {

    console.log("You are not boss and you can't add new task to other employees")

}
```