# Проект по А/Б тестированию с использованием bootstrap
### Описание эксперимента
У нас есть таблица, где числовая переменная – непрерывная. 
Задача – сравнить группы двумя способами: бутстрапом и u-тестом

### Описание колонок:
value – значения метрики <br/>
experimentVariant – Вариант теста (Control – контроль, Treatment – тест)

### Нужно сравнить результат между тестом и контролем по двум кейсам:
-применить бутстрап (с np.mean) и критерий mann-whitney, а потом сравнить p-value <br/>
-применить бутстрап (с np.median) и критерий mann-whitney, а потом сравнить p-value.
