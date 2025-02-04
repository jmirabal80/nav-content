---
    title: How to Assign Default Bins to Items 
    description: If you are using bins at a location, assigning default bins to your items can make the process of shipping, receiving, and moving your items much easier. When a default bin is assigned to an item, this bin is suggested every time you initiate a transaction for this item.
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 09/08/2017
    ms.author: edupont

---
# How to: Assign Default Bins to Items
If you are using bins at a location, assigning default bins to your items can make the process of shipping, receiving, and moving your items much easier. When a default bin is assigned to an item, this bin is suggested every time you initiate a transaction for this item. Default bins are defined in the **Bin Content** window.  

## To assign a default bin to an item
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bin Content Creation Worksheet**, and choose the related link.  
2.  Fill in the bin code and item information for each bin that you would like to set up as a default for an item. Make sure to select the **Default** field.  
3.  Choose the **Create Bin Content** action. Default bins are now assigned for your item.  

> [!NOTE]  
>  When an item is put away, if the item does not have a default bin assigned, the bin where the item is put away is assigned as the default.  

## To change the default bin for an item  
You may need to change the default bin assignment for an item or assign a default bin to a new item.    
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bin Contents**, and then choose the related link.  
2.  In the **Location Filter** field, select the appropriate location code.  
3.  Find the current default bin content entry for the item and clear the **Default Bin** check box.  
4.  Find the bin content line for the bin that you would like as the new default bin. Select the **Default Bin** check box.  

> [!NOTE]  
>  When an item is put away for the first time, and the item does not have a default bin assigned, the system will assign the bin where the item is put away as the default bin for the item.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
