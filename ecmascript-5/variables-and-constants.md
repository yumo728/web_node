## 变量

### 什么是变量
> 
> - 在 JavaScript 代码中，必须先声明一个变量，这个变量才能被使用。
> - JavaScript 中的变量是弱类型的，也称之为松散类型的。所谓弱类型/松散类型就是可以用来保存任何类型的数据。
var v = 100;
```

### 变量的声明

```javascript
var sum;// 值为undefined
```

- 一行代码声明多个变量

```javascript
var x, y, z;// 值为undefined
```

### 将变量的声明和初始化合写在一起

- 一行代码只声明一个变量并赋值:

```javascript
var sum = 100;// 值为 100
```

- 一行代码声明多个变量并赋值:

```javascript
var x = 0, y = 1, z = 2;
```

> **值得注意的是:** 等号（=）是赋值运算符。

- 必须以字母、下划线（_）、美元符号（$）开始。
- 不能以数字开头。
- 不能使用关键字和保留字作为名称。
- 由于 JavaScript 是区分大小写的，大写字母与小写字母并不冲突。
- 名称最好有明确的含义。
- 可以采用“下划线命名法”、“小驼峰命名法”或“大驼峰命名法” 之一，在开发团队内进行协调统一。

### 声明的问题
var msg = "this is message";// 值为 this is message
```

#### 遗漏的声明
var message;// 只声明未初始化
```

- 赋值操作
var message;// 只声明未初始化
```

## 常量

### 什么是常量
> 
> - 常量名习惯使用全大写形式。
> - ECMAScript 5新增了声明常量使用的关键字 const。
> - 如果省略const关键字，JavaScript会认为是一个变量。
var MY_CONST = 10;
```

- 在 ECMAScript 5 版本后，提供了关键字 `const` 定义常量。
const MY_FAV = 100;
```

> **值得注意的是:** 常量的声明，必须进行初始化操作，否则会报错误。
> 
> ```javascript
> const FOO; // SyntaxError: missing = in const declaration
> ```

### 常量的使用

```javascript
// 定义常量MY_FAV并赋值7
```