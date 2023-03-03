---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD for .NET API リファレンス
description: ImageOptionsBase 財産. デフォルトの置換フォントを取得または設定します PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合ラスターにエクスポートするときにテキストの描画に使用されるフォント デフォルト フォントの適切な名前を取得するには次のコード スニペットを使用できます  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily ファミリー  col.Families 文字列 defaultFontName  ファミリー0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /ja/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### プロパティ値

デフォルトの代替フォント。

### 例

次の例は、DefaultReplacementFont プロパティを使用して既定の置換フォントを変更する方法を示しています。

```csharp
[C#]

// このテストは、インストールされていないフォントを置き換える必要があるため、Konstanting Font をインストールしないでください。
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // このようにして、出力ごとに異なるフォントを使用できます 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### 関連項目

* class [ImageOptionsBase](../)
* 名前空間 [Aspose.PSD](../../imageoptionsbase/)
* 組み立て [Aspose.PSD](../../../)


