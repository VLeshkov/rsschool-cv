# Victor Leshkov
## Contacts
Email: leshkovvictor@gmail.com\
Telegram: @vleshkov
## About myself
30 years old. Beginner Frontend developer. My development path began in may 2021 when I started Python courses at Stepik. Currently I learn Frontent development at RS School and want to become a Junior Frontend Developer.
## Skills
Javascript, Typescript, HTML, CSS, Python, Git.
## Code Examples
Here are some katas solutions from Codewars.\
[Description](https://www.codewars.com/kata/57b06f90e298a7b53d000a86/), Javascript solution:
```javascript
function queueTime(customers, n) {
  let tills = [];
  for (let i = 0; i < n; i++) {
    tills.push(0);
  }
  
  for (let customer of customers) {
    tills[tills.indexOf(Math.min.apply(null, tills))] += Number(customer);
  }
  
  return Math.max.apply(null, tills);
}
```
[Description](https://www.codewars.com/kata/52223df9e8f98c7aa7000062/), Python solution:
```python
def rot13(message):
    alphabet = ''.join([chr(i) for i in range(97,123)])
    result = []

    shifted_alphabet =  ''.join(alphabet)[-13:] + ''.join(alphabet)[:-13]

    for letter in message:
        if letter.isalpha() == True:
            letter_index = alphabet.find(letter.lower())
            if letter.isupper() == True:
                result += shifted_alphabet[letter_index].upper()
            else:
                result += shifted_alphabet[letter_index]            
        else:
            result += letter

    return ''.join(result)
```
## Experience
Currently I learn Javascript at [learn.javascript.ru](https://learn.javascript.ru/) and JS/Frontend course at RS School.\
Certificates:
1. Программирование на Python (Python programming). [Certificate](https://stepik.org/cert/987494)
2. "Поколение Python": курс для начинающих (Python generation: beginners course). [Certificate](https://stepik.org/cert/1007833)
  
## Education
Self-taught. Stepik Python courses. RSSchool Frontend.
## English level
Advanced.