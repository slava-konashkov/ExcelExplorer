Работа с .xls .xlsx через phpoffice/phpspreadsheet

Результат представляю в сводной таблице:
| Row Numbers | Execution Seconds | .csv | .csv.zip | .xls | .xls.zip | .xlsx | .xlsx.zip |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 0.040378093719482 | 320 bytes | 395 bytes | 4.50 KB | 1.48 KB | 6.46 KB | 5.88 KB |
| 100 | 0.072196006774902 | 27.55 KB | 19.60 KB | 59.00 KB | 28.09 KB | 27.71 KB | 27.02 KB |
| 1000 | 0.73734402656555 | 275.18 KB | 194.13 KB | 556.00 KB | 251.59 KB | 219.22 KB | 213.04 KB |
| 5000 | 3.8420271873474 | 1.34 MB | 969.47 KB | 2.70 MB | 1.21 MB | 1.04 MB | 1.01 MB |
| 10000 | 7.692883014679 | 2.69 MB | 1.89 MB | 5.40 MB | 2.40 MB | 2.08 MB | 2.00 MB |
| 30000 | 24.259745121002 | 8.06 MB | 5.68 MB | 16.19 MB | 7.19 MB | 6.22 MB | 5.99 MB |
| 50000 | 43.667981863022 | 13.44 MB | 9.47 MB | 26.98 MB | 11.97 MB | 10.36 MB | 9.97 MB |
| 100000 | 88.528697013855 (1 min 28 sec) | 26.87 MB | 18.93 MB | 0 | 0 | 20.72 MB | 19.93 MB |
| 200000 | 225.89363098145(3 min 45 sec) | 53.74 MB | 37.86 MB | 0 | 0 | 41.47 MB | 39.86 MB |
| 500000 | 869.50662899017 (14 min 29 sec) | 134.35 MB | 94.65 MB | 0 | 0 | 103.69 MB | 99.63 MB |
| 1000000 | 2995.7989349365 (49 min 55 sec) | 268.71 MB | 189.30 MB | 0 | 0 | 207.36 MB | 199.23 MB |

Резюме: при любом раскладе сжатьій в zip .csv файл занимает меньше места (мелкими файлами до 100 строк считаю нужно принебречь)
