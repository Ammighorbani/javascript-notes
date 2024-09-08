# Practice

```
var sumPrice = 0

var userShopingCart = [
    {id: 1, name: "ps4", price: 90000},
    {id: 2, name: "ps5", price: 100000},
    {id: 3, name: "pen", price: 15000},
    {id: 4, name: "pencil", price: 5000},
    {id: 5, name: "keyboard", price: 4000000},
    {id: 6, name: "mouse", price: 2000000},
]

console.log(userShopingCart)



var lowerlistNoAdd = userShopingCart.filter(function(itemLowerNoAdd) {

    if (itemLowerNoAdd.price < 99000) {

        return itemLowerNoAdd

    }

})

var lowerlist = lowerlistNoAdd.map(function(itemLower) {

    return {id: itemLower.id, name: itemLower.name, price: (itemLower.price + 1000)}

})

console.log(lowerlist)


var higherlist = userShopingCart.filter(function(itemHigher) {

    if (itemHigher.price > 99000) {

        return itemHigher

    }

})

console.log(higherlist)


var LowerlistCalPrice = lowerlist.forEach(function(itemLowerAdd) {

    sumPrice += itemLowerAdd.price

})

var HigherlistCalPrice = higherlist.forEach(function(itemHigherAdd) {

    sumPrice += itemHigherAdd.price

})

console.log(sumPrice)


OR


var sumPrice = 0

var userShopingCart = [
    {id: 1, name: "ps4", price: 90000},
    {id: 2, name: "ps5", price: 110000},
    {id: 3, name: "pen", price: 15000},
    {id: 4, name: "pencil", price: 5000},
    {id: 5, name: "keyboard", price: 4000000},
    {id: 6, name: "mouse", price: 2000000},
]

console.log(userShopingCart)


var lowerItems = userShopingCart.filter(function(product) {

    if (product.price < 100000) {

        return product
        
    }

})

// console.log(lowerItems)

var postCost = lowerItems.length * 1000

var sumPriceCal = userShopingCart.map(function(product) {

    sumPrice += product.price

})

var totalPrice = sumPrice += postCost

console.log(totalPrice)
```