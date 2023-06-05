<img width="118" alt="image" src="https://github.com/ErefIect/newbie-frontend/assets/114394519/30ab1354-e1ae-4ad7-ae7c-7611c7e73cee">



## part1 
  make a simple todolist with the mock data to learn frontend basic concepts.

## part2

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

