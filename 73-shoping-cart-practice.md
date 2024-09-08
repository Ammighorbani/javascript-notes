# Practice

```
var sumPriceNumber = 0


var AllProducts = [
    {id: 1, name: "ps4", price: 10000000},
    {id: 2, name: "ps5", price: 30000000},
    {id: 3, name: "PC", price: 60000000},
    {id: 4, name: "laptop", price: 50000000},
    {id: 5, name: "mouse", price: 2000000},
    {id: 6, name: "keyboard", price: 40000000},
]


// AllProducts.forEach(function(porductItem) {
//     console.log(porductItem)
// })


var userShopingCart = [
    {id: 1, name: "ps4", price: 10000000},
    {id: 2, name: "ps5", price: 30000000},
    {id: 3, name: "PC", price: 60000000},
]



var userOperationInput = prompt("1. add to cart \n 2. remove of cart")

console.log(userOperationInput)

if (userOperationInput === "1") {

    AllProducts.forEach(function(porductItem) {

        console.log(porductItem)

    })


    var userItemInput = prompt("enter the name of product to add:")

    var isInProducts = AllProducts.some(function(product) {

        return product.name === userItemInput
    
    })
    
    // console.log(isInProducts)
    
    if (isInProducts === true) {
        
        var AddtoCart = AllProducts.some(function(product) {

            if (product.name === userItemInput) {
        
                if (userShopingCart.length === 0) {
        
                    userShopingCart.push({
                        
                        id: 1,
                        name: product.name,
                        price: product.price,
            
                    })
        
                } else {
        
                    userShopingCart.push({
                        
                        id: (userShopingCart[userShopingCart.length-1].id) + 1,
                        name: product.name,
                        price: product.price,
            
                    })
        
                }
        
            }
        
        })


        var sumPrice = userShopingCart.forEach(function(productPrice) {
            
            sumPriceNumber += productPrice.price
            
        })
        
        console.log(userShopingCart)
        console.log(sumPriceNumber)

    }

} else if (userOperationInput === "2") {

    userShopingCart.forEach(function(porductItem) {

        console.log(porductItem)
        
    })


    var userItemInput = prompt("enter the name of product to remove:")

    var isInProducts = AllProducts.some(function(product) {

        return product.name === userItemInput
    
    })

    // console.log(isInProducts)

    if (isInProducts === true) {

        var productIndex = userShopingCart.findIndex(function (product) {

            return product.name === userItemInput
        
        })
        
        // console.log(productIndex)
        
        var RemoveofCart = userShopingCart.splice(productIndex, 1)
        

        var sumPrice = userShopingCart.forEach(function(productPrice) {
            
            sumPriceNumber += productPrice.price
            
        })
        
        console.log(userShopingCart)
        console.log(sumPriceNumber)

    }

} else {
    console.log("we don't have your operation")
}
```