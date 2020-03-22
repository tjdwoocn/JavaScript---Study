# JavaScript(4) - Functions in JavaScript
> 자바스크립트의 Functions에 대해 알아보겠음

## Function in JavaScript?
- One of the fundamental building blocks in JavaScript

- A set of statements that performs a task or calculates a value

- 예시
```javascript
// Performing a task
function greet(name, lastName) {
    console.log('Hello ' + name + ' ' + lastName);
}
greet('Sungjae');
greet('Jany')
```
- Parameter: What we have here at the time of declaration (name)
- Argument: The actual value with supply for that parameter ('Sungjae')
- lastName parameter에 argument 값을 넣어주지 않으면 undefined 라고 출력됨

---
## Types of Functions
- 위의 예시는 Performing a task
- 아래 예시는 Calculating a value
```javascript
// Calculating a value
function square(number){
    return number * number;
}
let number = squre(5);
console.log(number); //25 출력
console.log(squre(5)); //25 출력, log 와 squre 2개의 function을 호출한 것

```



