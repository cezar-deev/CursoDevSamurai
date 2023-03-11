# Comparação estrita ( idêntico)

O JavaScript tenta converter dados, por isso o usso do `==` pode ocasionar problemas.

Ex:

```javascript
"1" == 1
1 == true
null == undefined
```

para solucionar este problemas utilizamos a comparação estrita( identico).

```javaScript
"1" === 1
1 === true
null === undefined
null !== undefined
```