# Exercise-Methods

let secretList  =[]
// using .unshift to add items to my empty array
secretList.unshift("Disguise kit","Grappling hook","Flashlight","map","snacks")
console.log(secretList);

// using .pop method to remove  Grappling Hook
secretList[1] = secretList.pop()
console.log(secretList);

// using.splice method to replace Flashlight with New Flashlight
secretList.splice(2, 1, "New Flashlight")
console.log(secretList);

// using .unshift() to add sunglasses to the beginning and using . push() to add first-aid-kit at the end
secretList.unshift("sunglasses")
console.log(secretList);

secretList.push("first-aid-kit")
console.log(secretList);

// converting the secretList into a single string with each item separated by a comma and a space using .join()
let secretList2 = secretList.join(",  ")
console.log(secretList2);


// adding batteries after new flashlight without revealing the method name
let secretList3 =[...secretList.slice(0, 4), "Batteries",...secretList.slice(4)]
let finalSecretList = secretList3.join(", ")
console.log(finalSecretList);

//  Checking if the list has a specific item ,like "map"
console.log(finalSecretList.includes("map"));








