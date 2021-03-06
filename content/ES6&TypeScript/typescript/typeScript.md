#TypeScript
ES6是当前的JavaScript版本。 TypeScript是ES6的超集，这意味着所有ES6功能都是TypeScript的一部分，但并非所有TypeScript功能都是ES6的一部分。 因此，TypeScript必须转换为ES5以在大多数浏览器中运行。
TypeScript的主要特征之一是添加类型信息，也因此得名。这种类型信息可以帮助JavaScript程序变得更易预测和推断。
类型让开发者写更明确的“合同”。 换句话说，函数签名等事情更加明确。

未使用TS：
```js
function add(a, b) {
  return a + b;
}

add(1, 3);   // 4
add(1, '3'); // '13'
```
使用TS：
```ts
function add(a: number, b: number) {
  return a + b;
}

add(1, 3);   // 4
// compiler error before JS is even produced
add(1, '3'); // '13'
```