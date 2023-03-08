# Gleb Shchemer #

## Contacts

* Location: Grodno, Belarus
* Phone: +375 33 682-20-83
* Email: gleb.shchemer@mail.ru
* GitHub: shchemer

## About me



## Skills

* HTML, CSS
* SCSS
* JavaScript
* Git
* Adobe Photoshop, Figma

## Code example

```
function fibNum(n) {
	while(isNaN(n)) {
		n = prompt('Entered value is not number, please enter a number');
	}
	
	if (+n === 0) {
		return 0;
	}
	else if (+n === 1 || +n === 2) {
		return 1;
	}
	else {
		let prevNum = 1,
			 nextNum = 1,
			 result = nextNum;
		for (let i = 2; i < n; i++) {
			nextNum += prevNum;
			prevNum = result;
			result = nextNum;
		}
		return result;
	}
}

fibNum(prompt('Enter a Fibonacci number', 0));
```

## Education

**College**: Grodno State Polytechnic College

**Speciality**: Technician programmer

## English

My english level is A2. I have completed English courses. I had experience of communicating with people from different countries. We talked about different topics (life, interests, people, etc.).