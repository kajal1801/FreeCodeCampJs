# Day 4

## Concepts

- Set
- Map
- RegExp
- Console Object

## Set

```
// An Empty set
const companies = new Set()
console.log(companies)

// A filled set
const languages = [
  'English',
  'Finnish',
  'English',
  'French',
  'Spanish',
  'English',
  'French',
]

const setOfLanguages = new Set(languages)
console.log(setOfLanguages)
```

- Set is a collection of elements. Set can only contains unique elements.
- To add an element in the set use the add() function
- To delete, use delete()
- To check for an element use has()
- To clear the set use clear()

## Map

```
// An Empty Map
const map = new Map()
console.log(map)

// A map with elements
countries = [
  ['Finland', 'Helsinki'],
  ['Sweden', 'Stockholm'],
  ['Norway', 'Oslo'],
]
const map = new Map(countries)
console.log(map)
console.log(map.size)
```

- Add values using set(key, value)
- Get value using get(key)
- Checking a key in Map using has()


## RegExp

```
let regEx = new RegExp('love', 'gi');
// or
let regExx = /love/gi;
```
- It is used to check if some patterns exist in a different data type or not.
- It takes two parameters: pattern and flag. (One required search pattern and an optional flag)
- Pattern can be a text or any form of pattern.
- Flag could be g, i, m, s, u or y. Here, g: 'global flag to check for pattern in the whole text', i: 'case insensitive flag', m: 'multiline flag'

### Functions:
- match():
```
const str = 'I love JavaScript'
const pattern = /love/
const result = str.match(pattern)
console.log(result)
```
Returns an array containing the pattern, index, input and group.

- search():
```
const str = 'I love JavaScript'
const pattern = /love/g
const result = str.search(pattern)
console.log(result)
```
Returns index of the match or -1.

- replace():
```
const txt = 'Python is the most beautiful language that a human begin has ever created.\
I recommend python for a first programming language'

matchReplaced = txt.replace(/Python|python/, 'JavaScript')
console.log(matchReplaced)
```
Executes a search for a match in a string, and replaces the matched substring with a replacement substring.

- test exact:
To check if the string is an exact match: It should have ^ starting and $ which is an end.

## Console Object

- `console.log`
- `console.error`
- `console.table`
- `console.time`
- `console.info`
- `console.assert`
- `console.group`
- `console.count`
- `console.clear`

Watched a video explaining the above functions from CodeWithHarry