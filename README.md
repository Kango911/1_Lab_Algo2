# Практическое занятие №1 (Анализ сложности алгоритмов)

# 1 часть. Цель задания – научиться на основе экспериментальных данных определять вычислительную сложность алгоритма.

1.	Создаете структуру (можно массив) на N элементов.
2.	Выбираете 3 различных алгоритма, работающих с вашей структурой (например, сортировка данных, поиск нужного элемента, подсчет кол-ва уникальных элементов и пр.). Здесь вы можете использовать уже готовые библиотеки и функции языка.
3.	Производите запуски этих алгоритмов при различных значениях N. Например, N = 1, 2, 5, 7, 10, 15, 20, 30, 50, 70, 100, 150, …. Данные, содержащиеся в элементах структуры, для каждого случая генерируются случайно. 
4.	При каждом запуске производите замер времени работы алгоритма.
5.	Для каждого алгоритма вы получаете набор замеров вида (N, t(N)). По этим точкам для каждого алгоритма вы стоите график.
6.	На основе получившихся графиков выдвигаете гипотезу о верхней оценки сложности работы каждого алгоритма. 
7.	Гипотезу подтверждаете путем построения соответствующего графика.

Пример 1.
 


![image](https://github.com/user-attachments/assets/8b85cdc9-3ac2-4f40-9158-48e28b546639)



Пример 2.



![image](https://github.com/user-attachments/assets/7ec363d9-2bbf-4e4b-bfc3-3e882f2a92f7)



# 2 часть. Цель задания – сравнить время работы алгоритма в различных случаях.

1.	Выбираете 2 различных алгоритма, работающих с вашей структурой. Алгоритмы можно повторить из прошлой части.
2.	Для каждого алгоритма у вас должно быть две реализации: первая – это с помощью готовых библиотек и функций языка, вторая – ваша собственная реализация.
3.	Для каждого алгоритма вы определяете, как должен выглядеть набор входных данных, чтобы он являлся лучшим случаем, средним и худшим.
4.	Для каждого алгоритма и его реализации («готовой» и «вашей») вы делаете запуски на этих наборах данных (лучший, средний, худший) при 3-х различных значениях N. Значения N должны быть: маленьким, средним, большим (здесь всё относительно и зависит от выбранного вами алгоритма, структуры и комплектации компьютера, на котором будет производиться запуск алгоритмов).
5.	Для каждого запуска (их всего получается 18 = 2 (алгоритма) * (набора данных) * 3 (три значения N)) вы производите замер времени работы алгоритма. Получившиеся данные вносите в таблицу.

![image](https://github.com/user-attachments/assets/07dbcc05-6b8e-4a88-af0b-dcdbd9446d6c)



