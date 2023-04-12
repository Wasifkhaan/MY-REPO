// PROGRAM 1

// function adder(num) {
//     return function(x) {
//       return x + num;
//     }
//   }
  
//   const add5 = adder(5);
  
//   console.log(add5(10)); // 15

// PROGRAM 2

// function searchArray(arr, value) {
//     // base case
//     if (arr.length === 0) {
//       return false;
//     }
//     // recursive case
//     if (arr[0] === value) {
//       return true;
//     } else {
//       return searchArray(arr.slice(1), value);
//     }
//   }

// PROGRAM 3

// function addParagraph(text) {
//     // Create a new paragraph element
//     let newParagraph = document.createElement('p');
  
//     // Set the text content of the new paragraph element
//     newParagraph.textContent = text;
  
//     // Append the new paragraph element to the bottom of the HTML document
//     document.body.appendChild(newParagraph);
//   }

// PROGRAM 4

// function addListItem(listItemText) {
//     var list = document.getElementById('list');
//     var newListItem = document.createElement('li');
//     newListItem.textContent = listItemText;
//     list.appendChild(newListItem);
//   }

//PROGRAM 5

// function changeBackgroundColor(element, color) {
//     element.style.backgroundColor = color;
//   }

//PROGRAM 6

// function storeObjectInLocalStorage(key, object) {
//     localStorage.setItem(key, JSON.stringify(object));
//   }

//PROGRAM 7
 
// function retrieveObject(key) {
//     const object = localStorage.getItem(key);
//     return JSON.parse(object);
// }

//PROGRAM 8

// function saveObjectToLocalStorage(obj) {
//     for (const key in obj) {
//       localStorage.setItem(key, obj[key]);
//     }
  
//     const newObj = {};
//     for (let i = 0; i < localStorage.length; i++) {
//       const key = localStorage.key(i);
//       const value = localStorage.getItem(key);
//       newObj[key] = value;
//     }
  
//     return newObj;
//   }
