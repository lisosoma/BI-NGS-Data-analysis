# Четвертое домашнее задание

## 1. Оценка качества исправления ошибок
Исправить риды с помощью любой программы (лучше Quake или BayesHamme), и приложив исправленные и исходные риды к геному, оценить следующие значения:




| | Error in corrected reads | Correct base in corrected reads | Base is absent in corrected reads|
|Error in raw data| Undetected error (false negative) |Detected & corrected error (true positive) |Detected and removed error (true positive)|
|Correct base in raw data| Falsely corrected error (false positive)|Correctly unmodified base (true negative)|Incorrectly removed base (false positive)|


Кратко опишите ваш метод вычисления этих значений.

## [Данные](https://drive.google.com/drive/folders/161iEpY6nUOs0ur1g2LVSRKuFXz4tNO41)

Данные: ecoli_400K_err_1.fastq, ecoli_400K_err_2.fastq

Референсный геном: MG1655-K12.first400K.fasta

Тестовые данные: ecoli_10K_err_1.fastq, ecoli_10K_err_2.fastq

Тестовый геном: MG1655-K12.first10K.fasta
