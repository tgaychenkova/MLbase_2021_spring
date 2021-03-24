# Homework2
## PART 1: Linear models
Все приложенные к этому проекту файлы нужны для выполнения первой части.

**Ожидаемый результат:** ноутбук *.ipynb с заполненными блоками кода

## PART 2: Metrics
Для второй части ничего из приложения не потребуется.

**Постановка задачи**:Необходимо реализовать функции accuracy_score, precision_score, recall_score, lift_score, f1_score (названия функций должны совпадать). 
Каждая функция должна иметь 3 обязательных параметра def precision_score(y_true, y_predict, percent=None). Добавлять свои параметры нельзя.

 - Нельзя использовать готовые реализации этих метрик
 - Если percent=None то метрика должна быть рассчитана по порогу вероятности >=0.5
 - Если параметр percent принимает значения от 1 до 100 то метрика должна быть рассчитана на соответствующем ТОПе
 - 1 - верхний 1% выборки
 - 100 - вся выборка
 - y_predict - имеет размерность (N_rows; N_classes)

**Ожидаемый результат:** файл *.py c реализованными функциями