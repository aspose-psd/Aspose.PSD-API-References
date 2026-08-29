---
title: "IPsdColorPalette"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "pasd カラーパレット"
type: docs
weight: 134
url: /ja/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

pasd カラーパレット
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | 生のカラーパレットエントリーデータを取得します。 |
| [getRawEntriesCount()](#getRawEntriesCount--) | 生のカラーパレットエントリ数を取得します。 |
| [getTransparentColor()](#getTransparentColor--) | 透過色を取得します。 |
| [getTransparentIndex()](#getTransparentIndex--) | 透過色のインデックスを取得します。 |
| [hasTransparentColor()](#hasTransparentColor--) | 透過色が存在するかどうかを示す値を取得します。 |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


生のカラーパレットエントリーデータを取得します。

値: 生のカラーパレットエントリデータです。

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


生のカラーパレットエントリ数を取得します。

値: 生のカラーパレットエントリ数です。

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


透過色を取得します。

値: 透明色です。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


透過色のインデックスを取得します。

値: 透明色のインデックスです。

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


透過色が存在するかどうかを示す値を取得します。

値: 透明色が存在する場合は true、そうでない場合は false。

**Returns:**
boolean
