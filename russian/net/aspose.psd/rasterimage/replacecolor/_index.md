---
title: "RasterImage.ReplaceColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RasterImage. Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв"
type: docs
weight: 460
url: /ru/net/aspose.psd/rasterimage/replacecolor/
---
{{< psd/tize >}}
## ReplaceColor(Color, byte, Color) {#replacecolor}

Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края.

```csharp
public void ReplaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColor | Color | Старый цвет, который будет заменён. |
| oldColorDiff | Byte | Допустимая разница в старом цвете, позволяющая расширить тон заменяемого цвета. |
| newColor | Color | Новый цвет, которым заменяется старый цвет. |

### См. также

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceColor(int, byte, int) {#replacecolor_1}

Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края.

```csharp
public virtual void ReplaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColorArgb | Int32 | Значение ARGB старого цвета, которое будет заменено. |
| oldColorDiff | Byte | Допустимая разница в старом цвете, позволяющая расширить тон заменяемого цвета. |
| newColorArgb | Int32 | Значение ARGB нового цвета, которым заменяется старый цвет. |

### См. также

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


