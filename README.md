# Javascript minification challenge for UP2IT

<a href="http://brocoders.com"><img src="https://media.licdn.com/dms/image/C4D0BAQEzIz_wy7_mng/company-logo_200_200/0?e=2159024400&v=beta&t=apDDtjWEU2IuVhVHGAW2voiAIB-OVRq6kiMNDGuA_gw" title="Brocoders" alt="Brocoders"></a>

Приветсвую тебя, путник! <br>
Если ты любишь челленджи и javascript также как их любим мы в Brocoders - то добро пожаловать! <br>
У тебя есть возможность выиграть ценные призы а также проявить свой скилл.

## Суть челленджа

Есть задача описание которой приведено ниже. Эта задача уже решена тут: <a href="https://codesandbox.io/s/loving-mccarthy-b1jsj">https://codesandbox.io/s/loving-mccarthy-b1jsj</a>. Необходимо отрефакторить код или написать новый, таким образом, чтобы получить решение с наименьшим количеством кода (символов).

## Описание задачи

Дан массив целых чисел, отсортированный по возрастанию. Есть функция `solution` (файл `./solution.js`) которая принимает массив чисел и возвращает строку с числами и интервалами, разделенными запятыми (см. пример ниже):
```javascript
solution([-6, -3, -2, -1, 0, 1, 3, 4, 5, 7, 8, 9, 10, 11, 14, 15, 17, 18, 19, 20]);
// returns "-6,-3-1,3-5,7-11,14,15,17-20"
```
Интервалы должны формироваться по следующим правилам:
  - если 3 и более чисел подряд возрастают на 1, то такие числа должны быть свернуты в интервал
  - интервал это первое и последнее из последовательных чисел, написанные через дефис
  - 2 последовательных числа не должны сворачиваться в интервал (например `[1, 2, 5, 6, 7] => "1,2,5-7"`)

Необходимо отрефакторить код или написать свой так чтобы он имел как можно меньше символов. При этом должны проходить все тесты на вкладке `Tests` в codesandbox:

<img src="https://drive.google.com/uc?export=view&id=18zOwDSeNI-THyMlTrJsh4jfCuO9UCNj-" title="Tests" alt="Tests">

## Как приинять участие?
1. Решаете задачу в codesandbox - в файле `solution.js`
2. Отпрвляете ссылку на свое решение (codesandbox) нам в телеграмм: `@ashelkov`
3. Подходите к стенду Brocoders чтобы подтвердиьт результат 
4. Мы проверяем решение и фиксируем результат - количество символов в коде
5. Решение с наименьшим количеством символов побеждает
6. Проверить количество симоволов в коде можно онлайн утилитой - <a href="https://www.charactercountonline.com">https://www.charactercountonline.com</a>
7. Промежуточные результаты можно смотреть тут: <a href="https://docs.google.com/spreadsheets/d/1FhhoN8qFA3goEVU4-4S7SVVaBPhLeWCVBtNn37nRtsE/edit?usp=sharing">challenge score table</a>

Да пребудет с Вами удача!
