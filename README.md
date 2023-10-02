# les_1
## firsts tаsks from karpov cources
#### Задание №7
Напишите программу, проверяющую стаж работы сотрудника. В переменной worker уже содержится список, содержащий значения как на 3-ем шаге (имя, фамилия, зарплата, стаж). Поместите в переменную status следующую строку:
user_name user_family is position
где user_name и user_family — имя и фамилия сотрудника, а position — одно из следующих значений:
'junior' — стаж меньше 2 лет
'middle' — стаж больше либо равен 2 лет и меньше или равен 5
'senior' — стаж больше 5 лет 
Пример данных, которые могут быть в worker:
worker = ['Olya', 'Silyutina', 350000, 3]
Hint: печатать результат не нужно, просто запишите его в переменную status.
#### Задание №9
Реализуйте цикл, который пробегается по уже созданному списку workers со значениями как на 3-ем и 7-ом шагах и выводит для каждого сотрудника следующую строку (то есть печатает её для каждого элемента списка):
user_name user_family is position
где user_name и user_family — имя и фамилия сотрудника, а position — одна из следующих строк:
'junior' — стаж меньше 2 лет
'middle' — стаж больше либо равен 2 и меньше или равен 5
'senior' — стаж строго больше 5 лет 
Сам список создавать не нужно, он уже находится в переменной workers. Пример данных, которые могут быть в workers:
workers = [['Ivan', 'Ivanov', 100000, 1], ['Petr', 'Petrov', 150000, 2], ['Sidor', 'Sidorov', 200000, 10]]
Note: в этом задании эти строки нужно печатать (используйте функцию print).
#### Задание №10
Поместите в список lst числа от 0 (n = 0) до 10 включительно (N = 10) c шагом 2 (dn = 2). Для этого используйте условие while.
Note: необходимо создать переменную lst, а переменные n, N, dn создавать не нужно. Итоговый список печатать тоже не нужно.
#### Задание №12
Теперь усложним задачу. Создайте словарь, где:
Ключом будет логин пользователя (login)
В качестве значения – словарь с характеристиками (как на предыдущем шаге) для этого пользователя
login	name	surname	age	salary	position
mvolkova	Masha	Volkova	25	60000	junior
pvoronov	Peter	Voronov	27	100000	junior
pparker	Peter	Parker	35	150000	middle
akarpov	Anatoly	Karpov	30	250000	senior
Таким образом, по ключу мы сможем получить всю информацию о нужном пользователе. Обратиться к такому элементу можно, например, с помощью: users_dict['mvolkova']['name'], где в первых скобках указывается логин (первый ключ), а во вторых – название характеристики, значение которой мы хотим получить.
Пример итоговой структуры:
{
'mvolkova' : {'name' : 'Masha', ...},
'pvoronov' : {'name' : 'Peter', ...}, 
...
}
Результат запишите в переменную users_dict.
