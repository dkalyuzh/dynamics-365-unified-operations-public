--- 
# required metadata 
 
title: Set up positions
description: This topic describes how positions are an important element of the lower level of an organization hierarchy. 
author: twheeloc
ms.date: 10/28/2021
ms.topic: business-process 
ms.prod:  
ms.technology:  
 
# optional metadata 
 
ms.search.form: DefaultDashboard, HcmWorkforceWorkspace, HcmWorkerActivityChart, HcmAllWorkersListPart, HcmPosition, HcmPositionNewPosition, HcmJobLookup, HcmPositionReportsToDialog, HcmPositionLookup, FinancialDimensionDefaultTemplatesLookup, DimensionLookup, HcmPersonnelManagementWorkspace
audience: Application User 
# ms.devlang:  
ms.search.scope: Human Resources
# ms.tgt_pltfrm:  
# ms.custom:  
ms.search.region: Global
# ms.search.industry: 
ms.author: twheeloc
ms.search.validFrom: 2016-06-30 
ms.dyn365.ops.version: Version 7.0.0 
---
# Set up positions

[!include [Applies to Human Resources](../includes/applies-to-hr.md)]



Positions are an important element of the lower level of an organization hierarchy. A position is an individual instance of a job. For example, the position, "Sales manager (East)," is one of the positions that is associated with the job, "Sales manager." A position exists in a department and may have only one worker associated with it. In this task we will walk through the steps required to create a position. This procedure is intended for Human Resources Specialists.

1. Select **Workforce management**.
2. Select **Open positions**.
3. Select **New** to open the drop-down dialog box.
4. In the **Job** field, enter or select a value.

    The **Job description**, **Title**, and **Full-time equivalent employment factor** fields are automatically copied from the selected job into the position.

5. ResolveChanges the Job.
6. Select **Create position**.
7. In the **Department** field, enter or select a value.
8. In the **Position type** field, enter or select a value.
9. In the **Compensation region** field, enter or select a value.

    The **Compensation region** field determines the compensation eligibility rules and fixed increase budgets that apply to an employee in that position.

10. In the **Available for assignment** field, enter a date and time.
11. Expand the **Position duration** section.

    The position duration is entered by default, based on activation and retirement dates that were entered earlier.

12. Expand the **Reports to position** section.

    When you assign a worker to a position that reports to another position, you create a direct reporting relationship between the workers who are assigned to the two positions.

13. Select **New to** open the drop-down dialog box.
14. In the **Reports to** field, enter or select a value.
15. Select **Create**.
16. Expand the **Worker assignment** section.
17. Expand the **Relationships** section.

    If your organization uses a matrix hierarchy or another custom hierarchy, you can set up position hierarchy types and then add reporting relationships to positions for each hierarchy type that you set up.

18. Select **Add**.
19. In the list, mark the selected row.
20. In the **Hierarchy name** field, enter or select a value.
21. In the **Reports to position** field, enter or select a value.
22. Expand the **Payroll** section.
23. In the **Pay cycle** field, enter or select a value.
24. In the **Paid by field**, enter or select a value.
25. In the **Annual regular hours** field, enter a number.

    The value that you enter is the number of regularly paid hours that the worker in this position is expected to work each year.

26. Expand the **Labor union** section.
27. Collapse the **Labor union** section.
28. Expand the **Financial dimensions** section.
29. In the **Distribution template** field, enter or select a value.
30. In the **Department** field, enter or select a value.
31. Select **Save**.



[!INCLUDE[footer-include](../includes/footer-banner.md)]
