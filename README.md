# hse_hw3_chromhmm

### Ссылка на блокнот: https://colab.research.google.com/drive/1czshlUE0fziXFf6-OxMS6e6iUJtjg6RC?usp=sharing

Файл cellmarkfiletable.txt находитс в папке data. Данные из папки с выдачей ChromHMM находятся в папке ChromHMM_output_result

Была выбрана K562. **Список 10-ти гистоновых меток и соответствующих имен файлов**:

H3k27ac	- H3k27acStdAlnRep1.bam

H3k27me3	- H3k27me3StdAlnRep1.bam

H3k36me3	- H3k36me3StdAlnRep1.bam

H3k4me1	- H3k4me1StdAlnRep1.bam

H3k4me2	- H3k4me2StdAlnRep1.bam

H3k4me3	- H3k4me3StdAlnRep1.bam

H3k9ac	- H3k9acStdAlnRep1.bam

H3k9me1	- H3k9me1StdAlnRep1.bam

H3k9me3	- H3k9me3StdAlnRep1.bam

H4k20me1 - H4k20me1StdAlnRep1.bam

## **Картинки из выдачи ChromHMM:**

<img width="233" alt="image" src="https://user-images.githubusercontent.com/67833171/161356418-603a8143-e889-49f3-bb65-5f68388320e4.png">

<img width="271" alt="image" src="https://user-images.githubusercontent.com/67833171/161356449-332401d3-f52a-4c9c-ad9e-ce403e1b1f54.png">

<img width="413" alt="image" src="https://user-images.githubusercontent.com/67833171/161356469-4c637076-b5f8-47c4-883d-8d3389a00b6a.png">

<img width="402" alt="image" src="https://user-images.githubusercontent.com/67833171/161356476-9b33d587-55c9-4830-9f07-675d2db894c9.png">

<img width="313" alt="image" src="https://user-images.githubusercontent.com/67833171/161356489-de67b9a3-72ce-450a-a98e-06b858ff4910.png">

## **Картинки из UCSC GenomeBrowser:**

<img width="472" alt="image" src="https://user-images.githubusercontent.com/67833171/161391379-868d8d1e-5522-4ba6-86d1-236626019a04.png">

<img width="473" alt="image" src="https://user-images.githubusercontent.com/67833171/161393339-a0c76644-76ab-41c7-9aba-bfe9e7b89b04.png">

<img width="469" alt="image" src="https://user-images.githubusercontent.com/67833171/161391508-4241a344-f2dc-4365-b409-e616f755dcc7.png">

## **Таблица:**

Состояния  | Расположение в геноме | Характерные гистоновые модификации | Название эпигенетического типа
--- | --- | --- | ---
**1** | ядерная ламина, на TES, гены | H3K9me1 и H3K27me3 (слабо выражены) | polycomb-repressed
**2** | ядерная ламина | - | heterochromatin
**3** | TES, гены, экзоны, ядерная ламина | H3K9me3, H3K36me3 (слабо выражена) | enhancer
**4** | гены, TES, экзоны | H3K36me3 | transcriptional area_1
**5** | TES, гены, экзоны | H3K7ac (слабо выражена), H3K9me1, H3K36me3, H3K4me1, H4K20me1 | transcriptional area_2
**6** | TES, гены, ядерная ламина | H3K4me1 | poised enhancer
**7** | TES, гены | H3K4me1, H3K27ac, H3K4me2, H3K9ac | transcriptional elongation
**8** | TES, TSS2kb, гены, экзоны | H3K4me1, H3K27ac, H3K4me2, H3K4me3, H3K9ac | weak promoter
**9** | почти равномерно  по всем (наиболее TSS, TSS2kb, CpG островки) | H3K4me2, H3K4me3, H3K4me1, H3K9ac | weak promoter/insulator
**10** | CpG островки, TSS, TSS2kb, экзоны | H3K27ac, H3K4me2, H3K4me3, H3K9ac | active promoter

## **Результат бонусного задания:**

