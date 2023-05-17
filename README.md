# es6代码块

在[JavaScript (ES6) code snippets](https://github.com/xabikos/vscode-javascript)基础上进行了扩充。感谢@xabikos

## Import 和 export
|prefix|说明/示例|
|-----|-------------------------------------------------------|
|imp→	| import fs from 'fs';|
|imn→	| import 'animate.css'|
|imd→	| import {rename} from 'fs';|
|ime→	| import * as localAlias from 'fs';|
|ima→	| import { rename as localRename } from 'fs';|
|rqr→	| require('fs');|
|req→	| const fs = require('fs');|
|mde→	| module.exports = {};|
|env→	| export const exportVariable = localVariable;|
|enf→	| export const functionName = (params) => {};|
|edf→	| export default function TM_FILENAME_BASE(params) {};|
|ecl→	| export default class className {}; |
|ece→	| export default class className extends baseclassName {};|

## Class helpers

|prefix|说明/示例|
|-----|-------------------------------------------------------|
|con→	|adds default constructor in the class constructor() {}|
|met→	|creates a method inside a class add() {}|
|pge→	|creates a getter property get propertyName() {return value;}|
|pse→	|creates a setter property set propertyName(value) {}|


## Various methods

|prefix|说明/示例|
|-----|-------------------------------------------------------|
|fre→	| forEach循环: array.forEach(currentItem => {})|
|fof→	| for...of循环: for(const item of object) {}|
|fin→	| for...in循环: for(const item in object) {}|
|anfn→| 箭头函数|
|nfn→	| const name = (params) => {}|
|dob→	| const {propertyName} = objectToDestruct;|
|dar→	| const [propertyName] = arrayToDestruct;|
|sti→	| set interval helper method setInterval(() => {});|
|sto→	| set timeout helper method setTimeout(() => {});|


## 字符串、对象、数组相关

|prefix|说明/示例|
|-----|-------------------------------------------------------|
|	inc | s.includes('Hello', 6) |
|	sw | s.startsWith('world', 6|
|	ew| s.endsWith('Hello', 5) |
|	rep| 'x'.repeat(3) |
| ois	| Object.is('foo', 'foo')|
|	oa | Object.assign(target, source1)|
|	okeys | Object.keys(obj)|
|	oval| Object.values(obj)|
|	oe | Object.entries(object);|
|	ofe | Object.fromEntries(arr);|
|	afrom | Array.from(object);|
|	aof| Array.of();|
|	afind| Array.find();|
|	afi | Array.findIndex(); |
|	afill | Array.fill(value);|

## 异步相关

|prefix|说明/示例|
|-----|-------------------------------------------------------|
|	afd| async 函数声明 |
|	afe | async 函数表达式 |
|	aaf | async 箭头函数 |
|	oaf | async 对象的方法 |
| prom| return new Promise((resolve, reject) => {});|
| cprom | const promise = new Promise(function(resolve, reject) {});|
| proma| const p = Promise.all([func1,func2]);|
| thenc	|.then((res) => {}).catch((err) => {});|
| thencf	|.then((res) => {}).catch((err) => {}).finally(() => {});|
|	patc | const p = Promise.all().then((res) => {}).catch((err) => {}); |


## Console

|prefix|说明/示例|
|-----|-------------------------------------------------------|
|cas→	| onsole.assert(expression, object)|
|ccl→	| console.clear()|
|cco→	| console.count(label)|
|cdb→	| console.debug(object)|
|cdi→	| console.dir|
|cer→	| console.error(object)|
|cgr→	| console.group(label)|
|cge→	| console.groupEnd()|
|clg→	| console.log(object)|
|clo→	| object with name console.log('object :>> ', object);|
|ctr→	| console.trace(object)|
|cwa→	| console.warn|
|cin→	| console.info|
|clt→	| console.table|
|cti→	| console.time|
|cte→	| console.timeEnd|

