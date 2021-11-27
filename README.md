# hse21_hw3

*Ссылка на GoogleColab:* https://colab.research.google.com/drive/1hUvRWecdyIJLg3CN6zBS3pUR27KXqJzy?usp=sharing

## Часть 1

### Сравнительная статистика из MultiQC
<img src="/img/general.png"/>

<p float="left">
  <img src="/img/fastqc_sequence_counts_plot.png " width="500" />
  <img src="/img/fastqc_per_base_sequence_quality_plot.png" width="500" />
  <img src="/img/fastqc_per_sequence_gc_content_plot.png" width="500" /> 
  <img src="/img/fastqc_per_sequence_quality_scores_plot.png" width="500" />
  <img src="/img/fastqc_sequence_duplication_levels_plot.png" width="500" />
  <img src="/img/fastqc-status-check-heatmap.png" width="500" />
</p>

### Кол-во уникально картированных чтений по каждому образцу
<img src="/img/unique.png"/>

### Статистика HTSeq. С помощью этого, узнаем количество чтений соответствует участкам генома, где не аннотировано ни одного экзона и количество чтений, которые могут принадлежать разным генам
<img src="/img/htseq.png"/>

### Посчитаем кол-во чтений, соответствующих хотя бы одному гену
<img src="/img/чтения.png"/>

### All_counts
<img src="/img/all_count.png"/>

## Часть 2. Анализ с помощью DESeq2

*Ссылка на GoogleColab - R:* https://colab.research.google.com/drive/1DZv9IxgXa_ATK9kw1_nv3OHIrXtkX55k?usp=sharing

### Ma-plot

График показывает Log2FC для генов. Здесь можно заметить, что большее количество дифференциально экспрессированных генов увеличило свою экспрессию.

<img src="/img/plotma.png"/>

### Heatmap

График показывает созависимость экспрессии генов из контрольных и репрограммированных образцов. На этой "карте" можно заметить, что экспрессия генов одинакова в одной группе образцов и отличается между группами.

<img src="/img/heatmap.png"/>

### Heatmap для первых 20 наиболее дифференциально экспрессированных генов
<img src="/img/pheatmap.png"/>

### Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах

<img src="/img/156.png"/>

Рассмотрим 3 гена с наибольшим положительным значением изменения экспрессии:

<img src="/img/1.png"/>

<img src="/img/2.png"/>

<img src="/img/3.png"/>
