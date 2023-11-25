# hse23_hw4
### Варфоломеева Анастасия Андреевна БПМ213

[Первая часть гугл коллаб](https://colab.research.google.com/drive/1sTSTh4nLfHB53qzvCqKi-JUNj6B4wihR?usp=sharing)\
[Вторая часть гугл коллаб](https://colab.research.google.com/drive/1YX1H1b6VNwT92D4yjwjuDtKo3luvOUFV?usp=sharing)


# Часть 1

## Проверка качества чтений по статистике из multiQC
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/1.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/2.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/3.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/4.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/5.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/6.png)
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/7.png)


## Общая статистика
![image](https://github.com/switerElly/hse23_hw4/blob/main/img/8.png)


## Таблица с информацией по образцам  
| ID | Тип | Общее число исходных чтений | Число и процент успешно откартированных чтений (не уникальные) | Число и процент успешно откартированных чтений (уникальные) | Общее число чтений, попавших на гены |
|----------|:----------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414635** | контрольный | 20956475  | 20715476, 98.85% | 18637053, 87.1% | 16463013 |
| **SRR3414636** | контрольный | 20307147  | 20073615, 98.85% | 18032679, 86.5% | 15942667 |
| **SRR3414637** | контрольный | 20385570  | 20149097, 98.84% | 18043406, 86.3% | 15914380 |
| **SRR3414629** | перепрограммированный | 21106089  | 20863369, 98.86% | 18573565, 88.0% | 16224313 |
| **SRR3414630** | перепрограммированный | 15244711  | 15077019, 98.90% | 13320505, 87.8% | 11583775 |
| **SRR3414631** | перепрограммированный | 24244069  | 23965262, 98.85% | 21159606, 87.5% | 18613501 |

# Часть 2. Анализ с помощью DESeq2

## MA-plot, показывающий Log2FC для генов  
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/plotMA.png)

## Тепловая карта зависимости экспрессии генов контрольных и репрограммированных образцов
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/heatmap_1.png)

## Тепловая карта 20 наиболее дифференциально экспрессированных генов
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/heatmap_2.png)

## Графики "Normalized counts" для генов, значимо поменявших свою экспрессию (видно, что точки у перепрограммированых и контрольных образцах сильно различаются)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/plot_1.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/plot_2.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/plot_3.png)
