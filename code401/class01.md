# Readings: Node Ecosystem, TDD, CI/CD

### first question
#### Describe (in plain English) what Array.map() does
` Array.map() `is an array method that loop throw an array and applied a callback function that change the return array from the method 
this is an example 
`
let number =[1,2,3,4]
let newNumber =number.map(element=>{
    return element * element
})
console.log(number)  // [1,2,3,4]
console.log(newNumber) // [1,4,9,16]
`
the map method always return an array , if there is no return statement it will be an array of undefined .
` Array.map() ` does not change the original array and return  an array with the same length of the original array



### second question
#### Describe (in plain English) what Array.reduce() does
` Array.reduce() `is an array method that loop throw an array and applied a callback function that reduce the array into  single value or its change the shape of the data 
 The callback takes 3 values accumulator,value and index
accumulator is a placeholder for what you want return it can be an array ,object or a value.
the return will be based on the accumulator.

so the callback takes 3 parameter and the reduce takes 2 parameter 
a callback and a initial value for accumulator
this is an example 
`
array.reduce(callback,initialAccumulator)
callback(acc,value,index)

`


### third question
#### Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
![Alt text](image/immmm.jpg)



### forth question
#### Explain promises as though you were mentoring a Code 301 level student
promises idea is to go find data then we you receive them apply this callback on them and if you didn't find them catch the problem on to them ...ez


### fifth question
#### Are all callback functions considered to be Asynchronous? Why or Why Not?
no because its depend on the documentation . if it async the callback will be async if not the callback wont be async





