---
title: License.SetLicense
second_title: Aspose.PSD for .NET API 参考
description: License 方法. 许可组件
type: docs
weight: 20
url: /zh/net/aspose.psd/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

许可组件。

```csharp
public void SetLicense(string licenseName)
```

### 评论

尝试在以下位置查找许可证：

1.显式路径。

2. 包含Aspose组件组装的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入式资源。

**笔记：**在 .NET Compact Framework 上，尝试仅在这些位置查找许可证：

1.显式路径。

2. 客户端调用程序集中的嵌入式资源。

### 例子

在此示例中，将尝试在包含 组件的文件夹中、在包含调用程序集的文件夹中、在入口程序集的文件夹中查找名为 的许可证文件，然后在调用程序集的嵌入资源. 可以是完整或短文件名或嵌入资源的名称。 使用空字符串切换到评估模式。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### 也可以看看

* class [License](../)
* 命名空间 [Aspose.PSD](../../license/)
* 部件 [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

许可组件。

```csharp
public void SetLicense(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含许可证的流。 |

### 评论

使用此方法从流中加载许可证。

### 例子

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### 也可以看看

* class [License](../)
* 命名空间 [Aspose.PSD](../../license/)
* 部件 [Aspose.PSD](../../../)


