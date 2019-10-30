# JS高级（ES5）

## 字符（数据）的类型

* 基本（值）类型 
  1. String：任意字符串
  2. Number：任意的数字
  3. Boolean：true/false
  4. undefined：undefined
  5. null：null
* 对象（引用）类型
  1. Object：任意对象
  2. Function：一种特别的对象（可以执行）
  3. Array：一种特别的对象（数值下标，内部数据是有序的）

## 判断

* typeof 
  * 返回数据类型的字符串表达（返回代表类型的字符串都是小写）
  * 可以判断，undefined/数值/字符串/布尔值
* instanceof
  * 判断对象的具体类型