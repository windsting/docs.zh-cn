---
title: Web 服务泛型序列化技术示例
ms.date: 03/30/2017
ms.assetid: cdc15ea4-f678-4729-8ebe-188ae720bef7
ms.openlocfilehash: 6549dc1c3d428a5fb74fe0212549ef3f3f6510d1
ms.sourcegitcommit: 9b552addadfb57fab0b9e7852ed4f1f1b8a42f8e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62018042"
---
# <a name="web-services-generics-serialization-technology-sample"></a>Web 服务泛型序列化技术示例
[下载示例](https://download.microsoft.com/download/4/7/B/47B2164C-E780-4B10-8DE4-2CB5B886E0A6/Technologies/Serialization/Xml%20Serialization/GenericsSerialization.zip.exe)  
  
 此示例演示如何在 ASP.NET Web 服务中使用和控制泛型的序列化。  
  
### <a name="to-build-the-sample-using-visual-studio"></a>使用 Visual Studio 生成示例  
  
1. 打开 Visual Studio，然后从“文件”菜单中选择“新建网站”。  
  
2. 在“新建网站”对话框的左侧窗格中选择所需的编程语言，然后从右侧窗格中选择“ASP.NET Web 服务”。  
  
3. 单击“浏览”，然后导航至 \CS\GenericsService 子目录。  
  
4. 选择 Service.asmx 以在 Visual Studio 中打开该文件。  
  
5. 在 **“生成”** 菜单上，单击 **“生成解决方案”**。  
  
> [!NOTE]
>  此列表中的前五个步骤是可选的。 .NET Framework 运行时将在首次请求该 Web 服务时自动生成该服务。  
  
> [!NOTE]
>  必须执行以下步骤，才能生成示例。  
  
1. 打开[!INCLUDE[fileExplorer](../../../includes/fileexplorer-md.md)]并导航到 \CS 子目录。  
  
2. 右键单击 GenericsService 子目录的图标，然后选择“共享和安全”。  
  
3. 在“Web 共享”选项卡中，选择“共享此文件夹”。  
  
> [!IMPORTANT]
>  请记下“别名”窗格中列出的虚拟目录名，因为需要用它来运行示例。  
  
### <a name="to-build-the-sample-using-internet-information-services"></a>使用 Internet 信息服务生成示例  
  
1. 打开“Internet Information Services”管理单元，然后展开“网站”。  
  
2. 左键单击“默认网站”，选择“新建”，然后选择“虚拟目录?”来创建“虚拟目录创建向导”。  
  
3. 单击“下一步”，输入虚拟目录的公共别名，然后再单击“下一步”。  
  
4. 输入保存示例的目录路径（通常是 \CS\GenericsService 子目录），然后单击“下一步”。 单击“下一步”完成向导。  
  
> [!IMPORTANT]
>  请记下“别名”窗格中列出的虚拟目录名，因为需要用它来运行示例。  
  
### <a name="to-run-the-sample"></a>运行示例  
  
1. 打开浏览器窗口，选择其地址栏。  
  
2. 类型`http://localhost/[virtual directory]/Service.asmx`，其中`[virtual directory]`表示生成该示例时创建的虚拟目录。  
  
## <a name="remarks"></a>备注  
 该示例将显示默认的 ASP.NET 页面，该页面包含指向 Web 服务定义的链接。 除了修改 Web 服务的源代码以外，还可以自定义其显示方式。 有关详细信息，请参阅[生成 XML Web services 客户端](https://docs.microsoft.com/previous-versions/dotnet/netframework-4.0/w3h45ebk(v=vs.100))。  
  
## <a name="see-also"></a>请参阅

- <xref:System.Collections.Generic>
- <xref:System.Web.Services>
- <xref:System.Xml.Serialization>
- [序列化](../../../docs/standard/serialization/index.md)
- [使用 ASP.NET 创建的 XML Web service 以及 XML Web Service 客户端](https://docs.microsoft.com/previous-versions/dotnet/netframework-4.0/7bkzywba(v=vs.100))
