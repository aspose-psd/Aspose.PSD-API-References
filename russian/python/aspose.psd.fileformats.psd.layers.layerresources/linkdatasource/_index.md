---
title: "Класс LinkDataSource"
type: docs
weight: 530
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Получает или задает значение, указывающее, заблокирован ли ресурс PSD.<br/>            Состояние блокировки ресурса, для активов библиотек Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Получает или задает время изменения ресурса, для активов Adobe® Photoshop® СС Libraries. |
| child_doc_id | string | r/w | Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Получает или задает ID текущего выбранного компа для дочернего документа, который будет -1, если ни один не выбран.<br/>            Компы — это композиции макета страницы, которые дизайнеры могут создавать. Используя слойные компы, вы можете создавать, управлять и просматривать несколько версий<br/>            макета в одном файле Adobe® Photoshop®. Слойный комп — это снимок состояния панели Layers. Слойные компы сохраняют три типа параметров слоев, но<br/>            это свойство получает идентификатор выбора слойного компа для Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| file_creator | string | r/w | Получает или задает создателя файла в ресурсе формата PSD LnkE / Lnk2. |
| file_type | string | r/w | Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE. |
| has_file_open_descriptor | bool | r/w | Получает или задает значение, указывающее, содержит ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId. |
| is_library_link | bool | r | Получает значение, указывающее, связывает ли этот источник данных PSD link с элементом Adobe® Photoshop® СС Library. |
| длина | long | r | Получает длину источника данных ссылки в байтах. |
| original_comp_id | int | r | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано.<br/>            Это свойство получает оригинальный идентификатор выбора слоя Comp для Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Слойовые компоновки в Smart Objects</see> |
| original_file_name | string | r | Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Получает тип глобального источника данных ссылки Adobe® Photoshop®, который может быть одним из следующих или отсутствовать:<br/>            Встроенный связанный файл liFD, соответствующий ресурсу PSD Lnk2Resource<br/>            Внешний связанный файл liFE, соответствующий ресурсу PSD LnkeResource<br/>            Псевдоним связанного файла liFA |
| unique_id | Guid | r | Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD. |
| version | int | r | Получает версию источника данных в ресурсе PSD LnkE / Lnk2. |


