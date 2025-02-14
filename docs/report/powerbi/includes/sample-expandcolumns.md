---
ms.topic: include
---

### Expand Area, Iteration, AssignedTo columns

The query returns several columns that you need to expand before you can use them in Power BI. Any entity pulled in using an OData **$expand** statement returns a record with potentially several fields. You need to expand the record to flatten the entity into its fields. Examples of such entities are: AssignedTo, Iteration, and Area. 

After closing the Advanced Editor and while remaining in the Power Query Editor, select the expand button on the entities you need to flatten.

1. Choose the expand button.

    > [!div class="mx-imgBorder"] 
    > ![Screenshot of Power BI transform data, Expand an entity column, ](/azure/devops/report/powerbi/media/odatapowerbi/expandcolumn.png)

1. Select the fields to flatten.

    > [!div class="mx-imgBorder"] 
    > ![Select the fields to flatten.](/azure/devops/report/powerbi/media/odatapowerbi/expandcolumn2.png)

1. The table now contains entity field(s).

    > [!div class="mx-imgBorder"] 
    > ![The table now contains entity field(s).](/azure/devops/report/powerbi/media/odatapowerbi/expandcolumn3.png)

1. Repeat steps 1 through 3 for all fields representing entities: Area, Iteration, AssignedTo.
