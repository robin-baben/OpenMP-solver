# Parallel solvers
Здесь представлены проекты, выполненные в рамках курса ***Параллелдьные методы решения задач***, читаемого студентам 1 курса магистратуры филиала МГУ им. М.В. Ломоносова в городе Сарове.

### Задание:
**Многопоточная реализация операций с сеточными
данными на неструктурированной смешанной сетке, параллельный решатель СЛАУ**

### Основные этапы:
- **Генерация сетки**

Строится  двумерная смешанно-элементная сетка на основе решетки, размера *Nx* на *Ny*. Нумерация узлов и клеток - слева направо, сверху вниз. Сеточные элементы - треугольники или четырехугольники. Клетки решетки делятся или не делятся на треугольники в соотношении, определяемом параметрами *k3*, *k4* (*k3* клеток делятся на треугольники, *k4* клеток не делятся (остаются четырехугольниками), и так по всем клеткам). На выходе - топология сетки в формате CSR, описывающая из каких узлов состоят элементы.



    
    
