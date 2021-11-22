# hse21_hw3  
## Часть 1
### Ссылка на коллаб для 1 части задания-* https://colab.research.google.com/drive/1O039qWJhQQzcikuRNy4WBOfh3M70WTzJ?authuser=2#scrollTo=IsQ33PGc435z
### Проверка качества чтений из fastQC:
![image](https://user-images.githubusercontent.com/60805733/142776373-05b11b52-924e-477f-8e98-42420cdf1f3f.png)  
![image](https://user-images.githubusercontent.com/60805733/142776385-9d5c4216-6283-468f-9622-ac1eb94a5b9c.png)  
![image](https://user-images.githubusercontent.com/60805733/142776392-b85c6c14-fe13-4f48-be6e-edde19a727b2.png)  
![image](https://user-images.githubusercontent.com/60805733/142776399-529eb5f7-c2de-4830-9b3b-dfb4bdf5523c.png)  
![image](https://user-images.githubusercontent.com/60805733/142776411-a7a90224-7d31-4d85-8d1f-66c6afb5d872.png)  
![image](https://user-images.githubusercontent.com/60805733/142776415-668765df-9d25-47c0-8ac1-cab95c8999c5.png)  
![image](https://user-images.githubusercontent.com/60805733/142776424-64035515-e04f-4b67-a028-cbc9a12bd12f.png)  
### Итоговая статистика
![image](https://user-images.githubusercontent.com/60805733/142776458-f388e537-633f-4e17-bf85-0fc809f3e379.png)  
### Уникально откартированные чтения для всех образцов:  
![image](https://user-images.githubusercontent.com/60805733/142800576-6f3a3f14-b979-429f-b770-8d1cc56c5281.png)  
### Смотрим сколько чтений не удалось приписать ни одному гену:
* __no_feature 1332692 – столько чтений соответствует участкам генома, где не аннотировано ни одного экзона
*  __ambiguous 735108 – столько чтений могут принадлежать разным генам
* Итого, общее число чтений, соответствующих хотя бы одному гену равно: 17825380 – 1332692 – 735108 = 15757580 Для каждого образца приводим эту статистику в отчете на Github 
![image](https://user-images.githubusercontent.com/60805733/142810569-f342aac0-46d7-47c0-9978-24edc16a1799.png)
### С помощью данный, приведенных выше, можно посчитать количество чтений, соответствующих хотя бы одному гену 
![image](https://user-images.githubusercontent.com/60805733/142816386-b3d787a5-7bdc-4744-8ec0-2bfacd4a5886.png)  
### Объединяем файлы с прочтениями в один - all_counts (столбцы - образцы, при чем c1, c2, c3 - контрольные образцы; r1, r2, r3 - перепрограммированные образцы)  
![image](https://user-images.githubusercontent.com/60805733/142817878-94b29c87-916e-4cea-bcea-0e599d5fef7c.png)
## Часть 2
### Ссылка на GoogleCola(part 2: DESeq):* https://colab.research.google.com/drive/174aQET9h9qfX1d2BlBC1_sDz0-FJ09kn?usp=sharing
### plotMA

### HeatMap

### Графики со значениями "Normalized counts" в двух группах образцов
