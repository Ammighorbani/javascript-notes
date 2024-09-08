# Practice

```
var sumPrice = 0

var products = [
    {id: 1, name: "ps4", price: 10000000},
    {id: 2, name: "ps5", price: 30000000},
    {id: 3, name: "PC", price: 60000000},
    {id: 4, name: "gaming monitor", price: 10000000},
    {id: 5, name: "laptop", price: 50000000},
    {id: 6, name: "mouse", price: 2000000},
    {id: 7, name: "key bourd", price: 6000000},
]

products.some(function (product1) {
    console.log(product1)
})


var userShopingCart = [
    {id: 1, name: "ps4", price: 10000000},
    {id: 2, name: "ps5", price: 30000000},
    {id: 3, name: "PC", price: 60000000},
]


var userInputItem = prompt("Enter which item do you want to add")
// console.log(userInputItem)

var reqPro;

var isInItem = products.some(function(product) {
    if (product.name === userInputItem) {
        reqPro = product
        return true
    }
})

if (isInItem === true) {
    userShopingCart.push({
        id: userShopingCart[userShopingCart.length-1].id + 1,
        name: reqPro.name,
        price: reqPro.price,
    })
} else {
    console.log("not found")
}

console.log(userShopingCart)

var prices = userShopingCart.forEach(function(priceItem) {
    sumPrice += priceItem.price
})

console.log(sumPrice)

OR

var sumPirce = 0

var AllProducts = [
    {id: 1, name: "pen", price: 10000},
    {id: 2, name: "ps4", price: 10000000},
    {id: 3, name: "ps5", price: 30000000},
    {id: 4, name: "phone", price: 15000000},
]

var showAllProducts = AllProducts.forEach(function(productItem) {
    console.log(productItem)
})


var userShopingCart = [

]


var userInputeOrder = prompt("enter your order name")


var userRequest;

var IsInProducts = AllProducts.some(function(product) {
    if (product.name === userInputeOrder) {
        userRequest = product
        return true
    }
})

// console.log(userRequest)


if (userInputeOrder.length == 0) {

    var addFirstUserOrder = userShopingCart.push({

        id: 1,
        name: userRequest.name,
        price: userRequest.price,

    })

} else if (userInputeOrder.length != 0) {

    var addUserOrder = userShopingCart.push({

        id: (userShopingCart.length) + 1,
        name: userRequest.name,
        price: userRequest.price,

    })

}


var showAllUserShopingCart = userShopingCart.forEach(function(item) {
    console.log(item)
})


var calculateSumPrice = userShopingCart.forEach(function(itemPrice) {
    sumPirce += itemPrice.price
    console.log(sumPirce)
})
```