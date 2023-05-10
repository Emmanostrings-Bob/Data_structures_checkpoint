# Data_structures_checkpoint


1. Algorithm:

Create an empty array to store the distinct elements.
Loop through the first set and check if the element is already present in the distinct elements array, if not, add it.
Loop through the second set and repeat step 2.
Calculate the sum of all elements in the distinct elements array.
Return the sum.


 Javascript code for the algorithm
// function sumOfDistinctElements(set1, set2) {
//     let distinctElements = [];
    
//     for(let i=0; i<set1.length; i++) {
//       if(!distinctElements.includes(set1[i])) {
//         distinctElements.push(set1[i]);
//       }
//     }
    
//     for(let i=0; i<set2.length; i++) {
//       if(!distinctElements.includes(set2[i])) {
//         distinctElements.push(set2[i]);
//       }
//     }
    
//     let sum = 0;
//     for(let i=0; i<distinctElements.length; i++) {
//       sum += distinctElements[i];
//     }
    
//     return sum;
//   }
  
//   //Example usage
//   let set1 = [3, 1, 7, 9];
//   let set2 = [2, 4, 1, 9, 3];
//   console.log(sumOfDistinctElements(set1, set2)); // Output: 13
  
  
  
  
  2. 2. Procedure dot_product(v1, v2):
Initialize ps to 0
For i from 1 to length of v1 do:
ps = ps + v1[i] * v2[i]
Return ps

Algorithm to determine orthogonality using procedure dot_product:
Input: n pairs of vectors v1 and v2 of IR
Output: whether each pair of vectors is orthogonal

For i from 1 to n do:
ps = dot_product(v1[i], v2[i])
If ps equals 0:
Print "Vectors", v1[i], "and", v2[i], "are orthogonal"
Else:
Print "Vectors", v1[i], "and", v2[i], "are not orthogonal"

Function dot_product(v1, v2):
Initialize ps to 0
For i from 1 to length of v1 do:
ps = ps + v1[i] * v2[i]
Return ps

Algorithm to determine orthogonality using function dot_product:
Input: n pairs of vectors v1 and v2 of IR
Output: whether each pair of vectors is orthogonal

For i from 1 to n do:
ps = dot_product(v1[i], v2[i])
If ps equals 0:
Print "Vectors", v1[i], "and", v2[i], "are orthogonal"
Else:
Print "Vectors", v1[i], "and", v2[i], "are not orthogonal"


// function sumOfDistinctElements(set1, set2) {
//     const distinctElements = [];
//     const unionSet = [...set1, ...set2];
  
//     for (let i = 0; i < unionSet.length; i++) {
//       const element = unionSet[i];
//       if (!distinctElements.includes(element)) {
//         distinctElements.push(element);
//       }
//     }
  
//     const sum = distinctElements.reduce((total, current) => total + current, 0);
//     return sum;
//   }
  
//   // Example usage:
//   const set1 = [3, 1, 7, 9];
//   const set2 = [2, 4, 1, 9, 3];
//   console.log(sumOfDistinctElements(set1, set2)); // Output: 13





