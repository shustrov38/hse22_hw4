# hse21_hw3  

# Часть 1  
[Ссылка на Google Colab для первой части](https://colab.research.google.com/drive/14lzDVSKQfnJOXECxgvL4kjQWa07ylIyc?usp=sharing)

## Проверка качества чтений из fastQC: сравнительная статистика из multiQC
![fastqc_general_statistics](res/fastqc_general_statistics.jpg)
![fastqc_sequence_counts_plot](res/fastqc_sequence_counts_plot.png)
![fastqc_per_base_sequence_quality_plot](res/fastqc_per_base_sequence_quality_plot.png)
![fastqc_per_sequence_quality_scores_plot](res/fastqc_per_sequence_quality_scores_plot%20(1).png)
![fastqc_per_sequence_gc_content_plot](res/fastqc_per_sequence_gc_content_plot.png)
![fastqc_per_base_n_content_plot](res/fastqc_per_base_n_content_plot.png)
![fastqc_sequence_duplication_levels_plot](res/fastqc_sequence_duplication_levels_plot.png)

## Общая статистика
![image](res/fastqc-status-check-heatmap.png) 

## Подсчет количества чтений, соответствующих одному или более гену 
![image](res/img1.png)

## Таблица с информацией по образцам  
| ID             |   Тип   | Общее число исходных чтений | Число и процент успешно откартированных чтений (не уникальные) | Число и процент успешно откартированных чтений (уникальные) | Общее число чтений, попавших на гены |
| -------------- | :-----: | :-------------------------: | :------------------------------------------------------------: | :---------------------------------------------------------: | :----------------------------------: |
| **SRR3414629** | reprogr |          21106089           |                            20510113                            |                            97.2%                            |               18375888               | 87.1% | 16049609 |
| **SRR3414630** | reprogr |          15244711           |                            14832680                            |                            97.3%                            |               13186139               | 86.5% | 11465324 |
| **SRR3414631** | reprogr |          24244069           |                            23547686                            |                            97.1%                            |               20928945               | 86.3% | 18408851 |
| **SRR3414635** | control |          20956475           |                            10395865                            |                            97.3%                            |               18428317               | 88.0% | 16275997 |
| **SRR3414636** | control |          20307147           |                            19757059                            |                            97.3%                            |               17825380               | 87.8% | 15757580 |
| **SRR3414637** | control |          20385570           |                            19847291                            |                            97.4%                            |               17844858               | 87.5% | 15736978 |

## ALL.counts содержит в себе все чтения  
![image](res/img2.png)
