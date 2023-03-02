# hse_hw2_chip

Татьяна Сидорова, Группа 2

[Ссылка на Колаб](https://colab.research.google.com/drive/1MBTUE6YXxupz3zQhIMVyv0CaPuNuHxe9#scrollTo=lT8If7HXiI9B)

## Анализ чтений FastQC

| ENCFF794NKI | ENCFF468EBP | ENCFF349YSG |
|:------------------------------------:|:------------------------------------:|:------------------------------------:|
|![image](https://user-images.githubusercontent.com/114301236/222522777-d17634bd-a025-4242-85fb-9f13613b908e.png)|![image](https://user-images.githubusercontent.com/114301236/222523100-a48c7444-0af2-4380-a925-6550af2b57e7.png) |![image](https://user-images.githubusercontent.com/114301236/222523149-776c6db2-f714-4fb9-9c3a-fd2bffc3dd3e.png)|
|![image](https://user-images.githubusercontent.com/114301236/222523499-25d2a247-aa98-41ee-81c5-b94181709fd2.png)|![image](https://user-images.githubusercontent.com/114301236/222523563-5c6352fc-a0a9-4d6b-9b85-1d4d2febf6f2.png)|![image](https://user-images.githubusercontent.com/114301236/222523659-74b23030-d9c3-4610-becb-c029371e3559.png)|
|![image](https://user-images.githubusercontent.com/114301236/222523876-6b349a9b-d036-4cb6-b7dc-49485b8ddc11.png)|![image](https://user-images.githubusercontent.com/114301236/222523939-3c069fa5-262c-46f3-83b5-becb15ba744e.png)|![image](https://user-images.githubusercontent.com/114301236/222524002-b69b7275-b030-4d67-8813-722eab2ab6a6.png)|
|![image](https://user-images.githubusercontent.com/114301236/222524163-89a81eaf-3661-4e9e-86f2-96f906a57be5.png)|![image](https://user-images.githubusercontent.com/114301236/222524236-08303dfb-73ad-4c74-8cd8-61e50e893658.png)|![image](https://user-images.githubusercontent.com/114301236/222524287-422a00b0-2854-437e-a5c1-be0277950231.png)|
|![image](https://user-images.githubusercontent.com/114301236/222524611-3636de0a-a4a1-43b3-8d15-eaa7028c1c1b.png)|![image](https://user-images.githubusercontent.com/114301236/222524658-788fb5c1-7ecd-4d88-841f-4346ec618d2b.png)|![image](https://user-images.githubusercontent.com/114301236/222524720-3c307340-1ca6-4a6b-ab45-2eb1dc55fcda.png)|
|![image](https://user-images.githubusercontent.com/114301236/222524868-1d459172-8268-4f02-afaa-9e0f4c428908.png)|![image](https://user-images.githubusercontent.com/114301236/222524958-9ecdca4b-5301-4e5f-80fd-bc12fa64879b.png)|![image](https://user-images.githubusercontent.com/114301236/222525040-c7a12c22-9fe3-4fc6-a74d-5668eccf1830.png)|
|![image](https://user-images.githubusercontent.com/114301236/222525179-24a901d2-63fe-4aff-a4a1-bb79875ad6ea.png)|![image](https://user-images.githubusercontent.com/114301236/222525220-f2916ee8-404f-43ef-bb69-17bdd124a370.png)|![image](https://user-images.githubusercontent.com/114301236/222525313-a3963df1-6f4b-4917-9aa1-95b45cf74173.png)|
|![image](https://user-images.githubusercontent.com/114301236/222525368-034e9e6f-bb27-4843-b38e-0e16a7d0aedc.png)|![image](https://user-images.githubusercontent.com/114301236/222525437-ef77a439-a4ee-4804-86b3-44abb30f6e0d.png)|![image](https://user-images.githubusercontent.com/114301236/222525507-5697c629-96f8-42c7-9226-63cf65d1cc54.png)|

## Выравнивание на 17 хромосому
| | Общее число ридов | Выровнившиеся уникально |Выровнившиеся уникально (%) |Выровнившиеся неуникально |Выровнившиеся неуникально (%)| Не выровнившиеся |Не выровнившиеся (%)|
|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|
|ENCFF794NKI|38877620|1655994|4.26%|3301153|8.49%|33920473|87.25%|
|ENCFF468EBP|72421515|3118033|4.31%|6976663|9.63%|62326819|86.06%|
|ENCFF349YSG|10167581|396363|3.90%|915992|9.01%|8855226|87.09%|

**Ответ на вопрос:** Процент выравниваний получился низким, поскольку чтения выравнены лишь на одну из 46 хромосом. 

## Диаграммы Эйлера-Венна

**Пересечение пиков 1 реплики и ENCODE**
|1 реплика с ENCODE|ENCODE с 1 репликой|
|:----------------:|:----------------:|
|![image](https://user-images.githubusercontent.com/114301236/222574015-9bca65dc-72f5-4d65-8704-05661782fff0.png)|![image](https://user-images.githubusercontent.com/114301236/222574083-76b403fa-70ef-46f0-9617-d27f01889cf5.png)|

**Пересечение пиков 2 реплики и ENCODE**
|2 реплика с ENCODE|ENCODE с 2 репликой|
|:----------------:|:----------------:|
|![image](https://user-images.githubusercontent.com/114301236/222574294-3ac71bd2-ee88-482d-9c5a-cd7fba8d5af3.png)|![image](https://user-images.githubusercontent.com/114301236/222574363-1011795a-1505-444d-aa9a-cb5520262b52.png)|

**Ответ на вопрос:** Малое количество пересечений связано с тем, что чтения выравнивались на одну хромосому, в то время как в базе данных ENCODE есть пики для всех хромосом. 


