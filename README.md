# AI CUP 隱私保護與醫學數據標準化競賽

## Introduction

近年來，人工智慧技術蓬勃發展，尤其在最近一年內，OpenAI、微軟和 Google 等公司紛紛引入並運用其自家發展的大型語言模型於相關產品中。這些應用包括 ChatGPT、Bing Search 和 Bard 等，顯示了大語言模型（Large Language Model）在各領域的應用潛力，大型語言模型在臨床醫療的應用也因此被視為是人工智慧未來在智慧醫療領域上非常重要的發展方向。然而在應用此類模型時，一般的使用者甚至是系統或程式開發人員往往未意識到跟大型語言模型互動時的隱私資訊問題，也因此可能導致重要隱密資訊的洩漏危機。此外，在訓練此類大型語言模型時所使用的訓練資料內，若是包含有真實的隱私資訊（如個人的姓名、電話、身分證號碼等），有一定的可能性因為大型語言模型的記憶能力與跟使用者的互動能力，導致隱私資訊的洩漏。

另一方面，在數位轉型的浪潮下，全球各級醫療院所逐步採用電子健康紀錄系統，讓電子健康紀錄成為重要的臨床醫學資料分析來源。然而醫療院所內的文本電子病歷（Electronic Medical Record），字裡行間往往充斥著與病患相關的隱私或隱密資訊；以下表為例，該電子病歷中的粗體文字描述了該病患的出生年月日、就診的時間資訊與負責診療的醫師等。此類片段的資訊一旦予以收集並在進行分析，往往有機會推導出該電子病歷中提及的病患真實身分，下圖顯示包含病患隱私資訊的文本報告範例（已去識別化)。

> D.O.B:  **09/08/2957**  
> Sex:  **F**  
> Collected: **14/02/3014 at 11:42**  
>Location:  **3 ARRIETTA CLOSE-POW**  
>DR AADLAND **ABRAHAM**  
>CLINICAL:  Lymphoma.  Duodenal uptake on PET scan.  
>Result required for multidisciplinary meeting on **Friday**.

## Files

- **Full_fine_tuining_160m.ipynb**: This notebook demonstrates the usage of the Full Fine-tuning method.

- **QLoRA_1.4B.ipynb**: This notebook showcases the implementation of QLoRA for specific task.

- **after_predict_country.ipynb**: This notebook covers post-prediction data processing, including data formatting, finding indices, and extracting country information.

## System Information
- **Operating System**: Fedora Linux 38
- **CPU**: 13th Gen Intel(R) Core(TM) i5-13600K
- **GPU**: NVIDIA RTX 4090 24GB
- **RAM**: 64GB



