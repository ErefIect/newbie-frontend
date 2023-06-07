<img width="118" alt="image" src="https://github.com/ErefIect/newbie-frontend/assets/114394519/30ab1354-e1ae-4ad7-ae7c-7611c7e73cee">

## part1 

### todolist
  make a simple todolist with the mock data to learn frontend basic concepts.

How to change elements' style in js?

```js
        const btns =
            document.querySelectorAll('button');
        for (let i = 0; i < btns.length; i++) {
            btns[i].addEventListener('click',
                e => {
                    document.querySelector('.active')
                        .classList
                        .remove('active');
                    e.target.classList
                        .add('active');
                })
        }
```
Performance Optimization
  One more efficient way than a for loop in the browser

## part2

### MVC and multi page application

### restful and single page application

### SSR CSR, SSG

# ES6查缺补漏

## 函数默认参数

1. 三目运算符

```js
const test = ( a, b = a == 1 ? 2 : 3 ) => { console.log(b) }
```
2. 函数

```js
const ts = () => { return Date.now }
const test = ( a = test() ) => { console.log(a) }
```

