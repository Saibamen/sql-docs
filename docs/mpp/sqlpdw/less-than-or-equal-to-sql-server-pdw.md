---
title: "&lt;= (Less Than or Equal To) (SQL Server PDW)"
ms.custom: na
ms.date: 07/27/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 93ec7fd7-c64b-4602-9df6-623822a029ab
caps.latest.revision: 16
author: BarbKess
---
# &lt;= (Less Than or Equal To) (SQL Server PDW)
Compares two expressions (a comparison operator). When you compare non-null expressions, the result is TRUE if the left operand has a value lower than or equal to the right operand; otherwise, the result is FALSE.  
  
![Topic link icon](../../mpp/sqlpdw/media/Topic_Link.gif "Topic_Link")[Syntax Conventions &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/syntax-conventions-sql-server-pdw.md)  
  
## Syntax  
  
```  
expression <=expression  
```  
  
## Arguments  
*expression*  
Any valid expression. Both expressions must have implicitly convertible data types. The conversion depends on the rules of data type precedence. For more information, see Data Type Precedence in [Data Types &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/data-types-sql-server-pdw.md).  
  
## Result Types  
**Boolean**  
  
## Remarks  
Comparisons involving null values, such as (NULL <= 100) or (100 <= NULL) return UNKNOWN; a comparison that results in UNKNOWN is not returned with either TRUE or FALSE results.  
  
## See Also  
[Common Metadata Query Examples &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/common-metadata-query-examples-sql-server-pdw.md)  
[Expressions &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/expressions-sql-server-pdw.md)  
[Data Types &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/data-types-sql-server-pdw.md)  
[Operators &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/operators-sql-server-pdw.md)  
[= &#40;Equals&#41; &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/equals-sql-server-pdw.md)  
[&#60; &#40;Less Than&#41; &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/less-than-sql-server-pdw.md)  
[&#62;= &#40;Greater Than or Equal To&#41; &#40;SQL Server PDW&#41;](../../mpp/sqlpdw/greater-than-or-equal-to-sql-server-pdw.md)  
  