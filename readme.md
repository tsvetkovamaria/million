# Миллионер

Пишем консольную версию телеигры "Кто хочет стать миллионером"

Описание игры:
Компьютер задает вопрос, показывает 4 варианта ответа. 
Пользователь вводит букву ответа.
Если ответ верный, то пользователь зарабатывает очки (100 за каждый ответ). 
Если ответ неверный, то пользователь теряет все очки и проигрывает. 

После каждого ответа показываем пользователю статистику: на сколько вопросов он ответил, сколько денег заработал. 

Если пользователь ответил на все вопросы, он выигрывает и получает красиво сообщение о сумме выигрыша.

Пользователь может в любой момент выйти из игры. После выхода из игры пользователь получает красивое поздравительное сообщение с суммой выигрыша.

Вопросы хранятся в файле questions.txt
Ответы хранятся в файле answers.txt
Прогресс игры сохраняется в файл progress.txt (только номера вопросов и ответы пользователя)


Дополнительные задания:
* Красиво оформить вопросы, ответы к ним и игровые сообщения. Поищите ASCII ART, поэспериментируйте самостоятельно с разными символами, рамками и т.п.
* Сделать прогрессивный выигрыш:
1 - 100
2 - 200
3 - 300
4 - 500
5 - 1000
6 - 2000
7 - 4000
8 - 8000
9 - 16000
10 - 32000
11 - 64000
12 - 125000
13 - 250000
14 - 500000
12 - 1000000
* Хранить суммы прогрессивного выигрыша в файле и перед началом игры получать их из файла.

* сделать суммы 1000 и 32000 несгораемыми
* сделать подсказки:
  * дать пользователю возможность выбрать подсказку 50/50 - остаются два ответа, один из которых однозначно правильный
  * дать возможность пропустить вопрос: пользователю показывают правильный ответ, но денег не получает
  * дать возможность заменить вопрос: вместо вопроса пользователь получает другой вопрос
* Shuffle: сделать еще вариант игры со случайными суммами за первые 10 вопросов. На первые 10 вопросов за каждый ответ пользователь получает случайную сумму. Несгораемых сумм в этом режиме нет
* дать пользователю выбрать в каком режиме он хочет играть: Progressive(обычный) и Shuffle(со случайными суммаи за первые 10 ответов)