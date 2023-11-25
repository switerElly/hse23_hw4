# hse23_hw4
### Варфоломеева Анастасия Андреевна БПМ213

[Первая часть гугл коллаб](https://colab.research.google.com/drive/1pAVSAzkO21VTxwMWb8LaridmVC9FijS-?usp=sharing)\
[Вторая часть гугл коллаб](https://colab.research.google.com/drive/1YX1H1b6VNwT92D4yjwjuDtKo3luvOUFV?usp=sharing)


# Часть 1

## Проверка качества чтений из fastQC: сравнительная статистика из multiQC
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_general_statistics.jpg)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_sequence_counts_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_base_sequence_quality_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_sequence_quality_scores_plot%20(1).png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_sequence_gc_content_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_per_base_n_content_plot.png)
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc_sequence_duplication_levels_plot.png)
## Общая статистика
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/fastqc-status-check-heatmap.png) 
## Подсчет количества чтений, соответствующих одному или более гену 
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/img1.png)
## Таблица с информацией по образцам  
| ID | Тип | Общее число исходных чтений | Число и процент успешно откартированных чтений (не уникальные) | Число и процент успешно откартированных чтений (уникальные) | Общее число чтений, попавших на гены |
|----------|:-------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414629** | перепрограммированный | 21106089 | 20510113 | 97.2% | 18375888 | 87.1% | 16049609 |
| **SRR3414630** | перепрограммированный | 15244711 | 14832680 | 97.3% | 13186139 | 86.5% | 11465324 |
| **SRR3414631** | перепрограммированный | 24244069 | 23547686 | 97.1% | 20928945 | 86.3% | 18408851 |
| **SRR3414635** | контрольный | 20956475 | 10395865 | 97.3% | 18428317 | 88.0% | 16275997 |
| **SRR3414636** | контрольный | 20307147 | 19757059 | 97.3% | 17825380 | 87.8% | 15757580 |
| **SRR3414637** | контрольный | 20385570 | 19847291 | 97.4% | 17844858 | 87.5% | 15736978 |
## ALL.counts содержит в себе все чтения  
![image](https://github.com/Vladm0z/hse21_hw3/blob/main/images/img2.png)
