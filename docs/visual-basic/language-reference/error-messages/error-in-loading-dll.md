---
title: 加载 DLL 时出错 (Visual Basic)
ms.date: 07/20/2015
f1_keywords:
- vbrID48
ms.assetid: 4226cd1f-028c-477d-88a5-cb57f7e0cdc8
ms.openlocfilehash: 5a26443a49b0b853f2f2188fb58d7ed907d671b4
ms.sourcegitcommit: 2701302a99cafbe0d86d53d540eb0fa7e9b46b36
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/28/2019
ms.locfileid: "64659628"
---
# <a name="error-in-loading-dll-visual-basic"></a>加载 DLL 时出错 (Visual Basic)
动态链接库 (DLL) 是一个库中指定`Lib`子句`Declare`语句。 此错误的可能原因包括：  
  
- 文件不是可执行文件的 DLL。  
  
- 文件不是 Microsoft Windows DLL。  
  
- DLL 引用不存在的另一个 DLL。  
  
- DLL 或引用的 DLL 不是在路径中指定的目录。  
  
## <a name="to-correct-this-error"></a>更正此错误  
  
- 如果该文件是源文本文件，因此不 DLL 的可执行文件，它必须编译并链接到 DLL 的可执行文件窗体。  
  
- 如果文件不是 Microsoft Windows DLL，获取 Microsoft Windows 等效。  
  
- 如果 DLL 引用不存在的另一个 DLL，获取引用的 DLL 并使其可用。  
  
- 如果 DLL 或引用的 DLL 不是由路径指定的目录中，将该 DLL 移动到引用的目录。  
  
## <a name="see-also"></a>请参阅

- [Declare 语句](../../../visual-basic/language-reference/statements/declare-statement.md)
