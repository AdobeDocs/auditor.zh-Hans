---
description: 此参考可提供有关 Adobe Experience Platform Auditor 执行标记一致性测试的更多信息。
seo-description: This reference provides more information about the tests Adobe Experience Platform Auditor performs for tag consistency.
seo-title: Tag consistency
title: 标记一致性
uuid: 16271dd6-3587-4f33-92f8-54ec4a3d6469
exl-id: 681cf2f8-e022-4fb0-a06a-b4986710f501
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# 标记一致性

此参考可提供有关 Adobe Experience Platform Auditor 执行标记一致性测试的更多信息。

Platform Auditor 的一致性测试旨在查找所有扫描的页面中是否存在不一致的内容。网站上所有页面中的这些值或配置应该是相同的，只有这样，才能确保数据收集是准确的。

<table id="table_4F9ED873BAF741D19BFB0F297B3A1FDB"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 测试 </th> 
   <th colname="col2" class="entry"> 标准 </th> 
   <th colname="col3" class="entry"> 推荐 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Analytics - 一致的代码版本 </b> </p> <p>权重：5 </p> <p><a href="https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/home.html" format="html" scope="external"> 其他信息</a> </p> </td> 
   <td colname="col2"> <p> 找到多个版本的 Analytics 代码。 </p> </td> 
   <td colname="col3"> <p>将 Analytics 的所有实例替换为当前版本。 </p> </td> 
  </tr> 
 </tbody> 
</table>
