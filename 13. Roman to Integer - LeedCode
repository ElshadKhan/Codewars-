// My solution

// const romanToInt = function(s) {
//   const objectDoubleValues = {'IV': 4, 'IX': 9, 'XL': 40, 'XC': 90, 'CD': 400, 'CM': 900}
//   const arrayDoubleValues = Object.keys(objectDoubleValues)
//   const objectValues = {'I': 1, 'V': 5, 'X': 10, 'L': 50, 'C': 100, 'D': 500, 'M': 1000}
//   const arrayValues = Object.keys(objectValues)
//   let count = 0
    
//   for (let i = 0; i < s.length; i++) {
//   console.log('123', s[i]);
//         if (arrayDoubleValues.indexOf(s[i]+s[i+1], 0) !== -1) {
//          count += objectDoubleValues[arrayDoubleValues[arrayDoubleValues.indexOf(s[i]+s[i+1])]]
//        } 
//        if(arrayDoubleValues.indexOf(s[i]+s[i+1], 0) === -1 && i === 0) {
//         count += objectValues[arrayValues[arrayValues.indexOf(s[i])]]
//        }
//        if(arrayDoubleValues.indexOf(s[i]+s[i+1], 0) === -1 && i !== 0 && i !== s.length -1 && arrayDoubleValues.indexOf(s[i-1]+s[i], 0) === -1) {
//         count += objectValues[arrayValues[arrayValues.indexOf(s[i])]]
//        }
//        if(arrayDoubleValues.indexOf(s[i]+s[i+1], 0) === -1 && i === s.length -1 && i !== 0 && arrayDoubleValues.indexOf(s[i-1]+s[i], 0) === -1) {
//         count += objectValues[arrayValues[arrayValues.indexOf(s[i])]]
//        }
//        console.log('count', count);
//        console.log('Elebele', objectValues[s[i]]);
//   }
//   return count
  
// };
// romanToInt('MXIV')

// №1 solution

const romanToInt = function(s) {
  const values = {'I': 1, 'V': 5, 'X': 10, 'L': 50, 'C': 100, 'D': 500, 'M': 1000}
  let count = 0
    
  for (let i = 0; i < s.length; i++) {
        if (values[s[i+1]] > values[s[i]]) {
         count += values[s[i+1]] - values[s[i]]
         i++
       } else {
        count += values[s[i]]
       }
       console.log('count', count);
       console.log('values[s[i]]', values[s[i]]);
       console.log('s[i]', s[i]);
  }
  return count
  
};
romanToInt('MXIV')
