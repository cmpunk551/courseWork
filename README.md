# Курсовая Работа 
Тема ВКР: «Разработка приложения для автоматизированного анализа и
сортировки файлов, загружаемых пользователем ПК»  
Объект исследования – файловая система ПК.    
Предмет исследования – методы анализа и сортировки файлов.    
 

Процессы верхнего уровня:   
* Создать требований для обработки (А1).
* Анализировать файлы (А2).    
* Сортировка файлов (А3).   
* Выдача результатов обработки (А4).   
## IDEF0
### Декомпозиция верхних уровней:
Точка зрения: ответственный за ведение архива. 

Цель моделирования: выделение автоматизируемых функций.  
* Контекстная диаграмма

  ![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/1.png)
* Декомпозиция блока Программа для обработки загружаемых файлов (А0)  

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/2.png) 
* Декомпозиция блока Анализировать файлы (А2)  

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/3.png)
* Декомпозиция блока Сортировка файлов (А3)   

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/4.png)  
## DFD
## Определение основных средств автоматизации

Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование) - Персональные Компьютеры (ПК).

Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные) - Многоуровневая (т.е. использующая удаленные БД и содержащая помимо клиентской и серверной дополнительные части).

Определение допустимых видов хранилищ и их размещения - Оперативная память, как промежуточное хранилище, а также Хранилище Файлов (именуемое далее, как "Файлы") на ПК.

## Разработка диаграмм

* Декомпозиция блока Создать требований для обработки (А1)  

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/5.png)  
* Декомпозиция блока Разместить файлы в каталоги (A33)

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/6.png)  
## UML диаграммы для курсового проекта
* ER-диаграмма для всех потоков:  

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/7.png)  
* ER-диаграмма для всех ролей:  

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/8.png)

* ER-диаграмма для всех модулей:

![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/9.png)  
## Расчёт трудозатрат на выполнение проекта:
* Определение количества функциональных точек:   
![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/10.png) 
* Трудозатраты по FPA IFPUG:  
![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/11.png)

Расчеты, выполненные первым методом FPA IFPUG, позволяют оценить сложность требуемых для создания информационной системы программных средств в 44 выровненных функциональных точках, а объем программного кода на языках программирования высокого уровня – 2068 строк кода.
* Трудозатраты по COCOMO II:  
![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/12.png)

Расчеты, выполненные вторым методом COCOMO II, позволяют оценить общие трудозатраты проекта разработки программных средств в 3 человеко-месяцев, а ожидаемую продолжительность проекта – в 5 месяцев. В результате того, что проект предварительно разрабатывался, он будет готов к защите ВКР.

### Эффект работы программы
![none](https://github.com/cmpunk551/courseWork/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/13.png)
Выполненные рассчёты позволяют сделать вывод, что разработанное ПО сократит время нна обработку документов почти на 99%.

## Вывод
Рассматриваемая программа позволить значительно экономить время специалистов, работающих с файлами, а в частности, с документами. Анализируемая точка зрения работника, ведущего архив, позволила оценить полезность и эффетивность создаваемого программного продукта.
Данный проект будет реализован к сроку сдачи ВКР, и наглядно продемонстрирует свои достоинства.
