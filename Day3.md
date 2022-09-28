# Day 3

### Concepts

- forEach
- map

#### ForEach

```
const a = [1, 2, 3];
a.forEach((value, index, array) => {
    // function logic
});
```
- helps to iterate through an array.
- Doesn't returns anything.


#### Map

```
let arr = [45, 23, 21];
arr.map((value) => {
    console.log(value)
});
```

- map creates a new array from an existing one.
- map looks like forEach but in forEach we just iterate through the array and don't create a new array.
- Returns an Array.

#### Filter

```
let arr = [45, 23, 21, 0, 3, 5];
let a = arr.filter((value) => {
    return a<10;
});
console.log(a);
```

- filters the requested values from an array and creates a new array for the filtered values.
- It doesn't modifies the original array.
- Return an array.

#### Reduce

```
let arr = [1, 2, 3, 5, 2, 1];
let myArr = arr.reduce((value1, value2) => {
    return value1 + value2;
});
console.log(myArr);
// Output: 14 
```

- It redcues the array by doing the specified operation to a single value.
- Returns a value.