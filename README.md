# hse21_hw3  
## Часть 1
### Ссылка на коллаб для 1 части задания-* https://colab.research.google.com/drive/1O039qWJhQQzcikuRNy4WBOfh3M70WTzJ?authuser=2#scrollTo=IsQ33PGc435z
### Проверка качества чтений из fastQC:
![alt](./images/статистика.png)  
![alt](./images/fastqc(2).png)  
![image](https://user-images.githubusercontent.com/60805733/142776392-b85c6c14-fe13-4f48-be6e-edde19a727b2.png)  
![alt](./images/FASTqc(1).png)   
![alt](./images/FASTqc.png)  
![image](https://user-images.githubusercontent.com/60805733/142776415-668765df-9d25-47c0-8ac1-cab95c8999c5.png)  
![alt](./images/fastqc(3).png)  
### Итоговая статистика
![image](https://user-images.githubusercontent.com/60805733/142776458-f388e537-633f-4e17-bf85-0fc809f3e379.png)  
### Уникально откартированные чтения для всех образцов:  
![alt](./images/подсчет уникальных чтений.png)  
### Смотрим сколько чтений не удалось приписать ни одному гену:
* __no_feature 1332692 – столько чтений соответствует участкам генома, где не аннотировано ни одного экзона
*  __ambiguous 735108 – столько чтений могут принадлежать разным генам
* Итого, общее число чтений, соответствующих хотя бы одному гену равно: 17825380 – 1332692 – 735108 = 15757580 Для каждого образца приводим эту статистику в отчете на Github 
* ![alt](./images/подсчет.png)
### С помощью данный, приведенных выше, можно посчитать количество чтений, соответствующих хотя бы одному гену 
![image](https://user-images.githubusercontent.com/60805733/142816386-b3d787a5-7bdc-4744-8ec0-2bfacd4a5886.png)  
### Объединяем файлы с прочтениями в один - all_counts (столбцы - образцы, при чем c1, c2, c3 - контрольные образцы; r1, r2, r3 - перепрограммированные образцы)  
![image](https://user-images.githubusercontent.com/60805733/142817878-94b29c87-916e-4cea-bcea-0e599d5fef7c.png)
## Часть 2
### Ссылка на GoogleCola(part 2: DESeq):* https://colab.research.google.com/drive/174aQET9h9qfX1d2BlBC1_sDz0-FJ09kn?usp=sharing
### plotMA

### HeatMap

### Графики со значениями "Normalized counts" в двух группах образцов
