```js
var x = [,, "foo", "bar"]

var [,, y, z] = x

y //: string
z //: string
```
```json
[
  {
    "id": "d867b860-7aee-11e6-a2df-29b1c43b02c6",
    "name": "x",
    "addr": "/x/",
    "kind": "v",
    "type": "[string]",
    "lineno": 1,
    "origin": {
      "!span": "4[0:4]-5[0:5]",
      "!type": "[string]",
      "!data": {
        "isConstructor": false,
        "type": "Array.prototype"
      }
    },
    "tagfile": "__DIR__/array_holes.js"
  },
  {
    "id": "d867df70-7aee-11e6-a2df-29b1c43b02c6",
    "name": "y",
    "addr": "/y/",
    "kind": "v",
    "type": "string",
    "lineno": 3,
    "origin": {
      "!span": "35[2:8]-36[2:9]",
      "!type": "string",
      "!data": {
        "isConstructor": false,
        "type": "String.prototype"
      }
    },
    "tagfile": "__DIR__/array_holes.js"
  },
  {
    "id": "d8680680-7aee-11e6-a2df-29b1c43b02c6",
    "name": "z",
    "addr": "/z/",
    "kind": "v",
    "type": "string",
    "lineno": 3,
    "origin": {
      "!span": "38[2:11]-39[2:12]",
      "!type": "string",
      "!data": {
        "isConstructor": false,
        "type": "String.prototype"
      }
    },
    "tagfile": "__DIR__/array_holes.js"
  }
]
```
```ctags
x	__DIR__/array_holes.js	/x/;"	v	lineno:1	type:[string]
y	__DIR__/array_holes.js	/y/;"	v	lineno:3	type:string
z	__DIR__/array_holes.js	/z/;"	v	lineno:3	type:string
```
