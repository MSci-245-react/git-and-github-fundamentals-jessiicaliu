# Equality in JavaScript

One thing I learned in Lecture 1.3 was the difference between `==` and `===` in JavaScript. The `==` operator automatically converts values to the same type before comparing them, while `===` checks both the value and the data type.

```javascript
0 == ""
```

```
true
```

- `==` performs type coercion (surprises!)
- `===` checks type AND value (predictable)
