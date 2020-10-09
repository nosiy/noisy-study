# noisy-study


instanceof and isPrototypeOf()
constructor 方法是类的构造函数，是一个默认方法，通过 new 命令创建对象实例时，自动调用该方法

Array.from方法用于将两类对象转为真正的数组：类似数组的对象（array-like object）和可遍历（iterable）的对象（包括ES6新增的数据结构Set和Map）。

Object 构造函数创建一个对象包装器。
https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object


Object.keys() 方法会返回一个由一个给定对象的自身可枚举属性组成的数组，数组中属性名的排列顺序和正常循环遍历该对象时返回的顺序一致 。

Object.defineProperty()
给对象添加一个属性并指定该属性的配置。

Object.assign 方法用于对象的合并，将源对象（source）的所有可枚举属性，复制到目标对象（target）。
Object.assign()要拷贝的对象只有一个不可枚举属性invisible，这个属性并没有被拷贝进去。属性名为 Symbol 值的属性，也会被Object.assign()拷贝
Object.assign()可以用来处理数组，但是会把数组视为对象。
Object.assign([1, 2, 3], [4, 5]) // [4, 5, 3]