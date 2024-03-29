---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD for .NET API 参考
description: ImageOptionsBase 财产. 获取或设置默认替换字体导出到光栅时将用于绘制文本的字体如果系统中未显示 PSD 文件中的现有图层字体 可以使用下一个代码片段来获取默认字体的正确名称 System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName  复制代码
type: docs
weight: 20
url: /zh/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

获取或设置默认替换字体（导出到光栅时将用于绘制文本的字体，如果系统中未显示 PSD 文件中的现有图层字体）。 可以使用下一个代码片段来获取默认字体的正确名称: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); 复制代码

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### 适当的价值

默认替换字体。

### 例子

以下示例显示如何使用 DefaultReplacementFont 属性更改默认替换字体。

```csharp
[C#]

// 请不要安装 Konstanting Font，因为这个测试应该替换未安装的字体
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // 这样你就可以为不同的输出使用不同的字体 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### 也可以看看

* class [ImageOptionsBase](../)
* 命名空间 [Aspose.PSD](../../imageoptionsbase/)
* 部件 [Aspose.PSD](../../../)


