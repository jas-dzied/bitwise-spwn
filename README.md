# bitwise-spwn
A library to perform bitwise operations on binary strings

# Usage

```
$.print(bitwise::and("110011", "101010"))
$.print(bitwise::or("110011", "101010"))
$.print(bitwise::xor("110011", "101010"))
$.print(bitwise::not("110011"))

$.print(bitwise::lshift("110010"))
$.print(bitwise::rshift("010011"))
$.print(bitwise::lrotate("110010"))
$.print(bitwise::rrotate("010011"))
```

Output:
```
100010
111011
011001
001100
100100
001001
100101
101001
```
