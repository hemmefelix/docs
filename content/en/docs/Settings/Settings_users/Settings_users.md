---
title: "Settings > Users"
linkTitle: "Users"
date: 2023-05-01   
weight: 220
tags: ["subtopic"]   
---

The Users section in the Settings app provides configuration options for managing user records, including user information, patron blocks, fee/fine processing, permissions, and service points.

## Permissions

The following are all the permissions for Users in the Settings app:

-   **Settings (Users): Can create, edit and remove address types.** 
-   **Settings (Users): Can create, edit and remove all feefines-related entries.**
-   **Settings (Users): Can create, edit and remove comments.**
-   **Settings (Users): Can create, edit and remove feefines.**
-   **Settings (Users): Can create, edit and remove owners.**
-   **Settings (Users): Can create, edit and remove patron blocks limits.**
-   **Settings (Users): Can create, edit and remove patron blocks templates.**
-   **Settings (Users): Can create, edit and remove patron groups.**
-   **Settings (Users): Can create, edit and remove payments.**
-   **Settings (Users): Can create, edit and remove permission sets.**
-   **Settings (Users): Can create, edit and remove refunds.**
-   **Settings (Users): Can create, edit and remove transfer accounts.**
-   **Settings (Users): Can create, edit and remove transfer criteria.**
-   **Settings (Users): Can create, edit and remove waives.**
-   **Settings (Users): Can create, edit, and view custom fields.**
-   **Settings (Users): Can create, edit, view and delete custom fields.**
-   **Settings (Users): Can view and edit patron blocks conditions.**
-   **Settings (Users): Can view custom fields.**
-   **Settings (Users): Create, edit, and view departments.**
-   **Settings (Users): Create, edit, view, and delete departments.**
-   **Settings (Users): View departments.**

## Settings \> Users \> Permission sets

Use this setting to create permission sets for your library. Permission sets are customized collections of permissions that can be assigned to users. For example, you can create permission sets that correspond to specific job roles and assign the set, rather than each individual permission, to all library staff with that role.

Additionally, if permissions change because of a new release, a FOLIO administrator can edit the permission set for a particular role to update the assigned permissions. The change to the permission set then propagates out to the users who have that permission set assigned, and the administrator doesn't have to update permissions for each individual user.

For more information about permissions, see [Platform Essentials > Permissions](../platform-essentials/permissions/).

### Create a permission set

1.  In the **Permission sets** pane, click **New**.
2.  To name the permissions set, enter a **Permission set name**. The system does not automatically enforce uniqueness in naming permission sets. To avoid creating permission sets with duplicate display names, make sure this new permission set has a unique name. 
3.  Optional: Enter a **Description** of the permission set.
4.  Under **Assigned permissions**, click **Add permission**. You can assign individual permissions or existing permission sets to the new permission set. 
5.  In the **Select Permissions** modal, search and filter by **Permission type** and/or **Permission assignment status** or type in the name of the permission or permission set into the search box. 
6. Select the permission(s) or permission set(s) to assign to the new permission set. 
7.  Click **Save & close**. The permission(s) or permission set(s) are added to the new permission set.
8.  Click **Save & close**. The new permission set is saved.

### Edit a permission set

1.  In the **Permission Sets** pane, find the permission set you want to edit and select it.
2.  Click **Edit**.
3.  Make your desired changes to the permission set.
4.  Click **Save & Close**. 

### Delete a permission set

Note: A permission set can be deleted even if it is currently assigned to a user. Deleting the permission set removes it from the users to whom it was assigned.

1.  In the **Permission Set** pane, find the permission set you want to delete and select it.
2.  Click **Edit**.
3.  In the **Edit** window, click **Delete**.
4.  In the **Delete permission set?** dialog, click **Delete**. A confirmation message appears and the permission set is deleted.

## Settings \> Users \> Patron Groups

Use this setting to create patron groups for your library. Patron groups are classes of library users. For example, you may want to create a patron group called Faculty or Undergraduates.

Only one patron group can be assigned to a user record. Patron groups are also used to create [Circulation rules](../../settings_circulation/settings_circulation/#settings--circulation--circulation-rules).

### Create a patron group

1.  In the Settings app, select **Users \> Patron groups**. 
2.  In the **Patron groups** pane, click **New**.
3.  Enter a name for the **Patron group** in the box. Patron group names must be unique and should not contain any punctuation.
4.  (Optional): Enter a **Description** of the patron group.
5.  (Optional): Enter a number in the **Expiration date offset (days)** box. This number represents the number of days of active status for user records assigned to the patron group.  
6.  Click **Save**. The **Patron group** is saved.

### Edit a patron group

1.  In the Settings app, select **Users \> Patron groups**.
2.  In the **Patron groups** pane, find the **Patron group** you want to edit and click the **pencil icon** in the **actions** column. 
3.  Make your changes to the **Patron group**, **Description**, or **Expiration offset date (days)**. 
4.  Click **Save**. The changes to the **Patron group** are saved.

### Delete a patron group

A patron group can be deleted only if it is no longer applied to any user records. To delete a patron group, you must first check that no users are currently assigned to that group.

To see the number of user records assigned to a patron group: 

-   In the Users app, in the **User search** pane, select the checkbox next to the appropriate Patron group. 
-   The list of user records assigned to that patron group appears in the **User search results** pane. 
-   The number of records found displays at the top of the pane. 
-   If *0 records found* appears, the patron group can be deleted. 

To delete a patron group, follow these steps:

1.  In the Settings app, select **Users \> Patron groups**.
2.  In the **Patron groups** pane, find the patron group you want to delete and click the **trash can icon** in the **Actions** column.
3.  In the **Delete Patron group** dialog, click **Delete**. A confirmation message appears and the patron group is deleted.

## Settings \> Users \> Address Types

Use this setting to configure address types. Address types are used to categorize the addresses that are entered in the [Contact information](../users/#contact-information) section of a user record. For example, you may want to create the address types: office, work, or home address.

Note: Address types should be configured before bulk loading of patrons occurs if mailing addresses are to be stored.

### Create an address type

1.  In the Settings app, select **Users \> Address Types**.
2.  In the **Address Types** pane, click **New**.
3.  Enter a name for the **Address Type** in the box. The Address Type must be unique.
4.  Optional: Enter a **Description** of the Address Type.
5.  Click **Save**. The **Address Type** is created.

### Edit an address type

1.  In the Settings app, select **Users \> Address Types**. 
2.  In the **Address Types** pane, find the **Address Type** you want to edit and click the **pencil  
     icon** in the **Actions** menu. 
3.  Make your changes to the **Address Type** or **Description**.
4.  Click **Save**. The **Address Type** is saved.

### Delete an address type

An address type can be deleted only if it is not assigned to any user records. To delete an **Address Type**, you should first check that no user records are assigned the address type. 

To see the number of user records assigned to an address type:

- In **Settings \> Users \> Address Types**, the number of user records assigned to an **Address Type** will display in the **# of Addresses** column. 
- If a *-* is displayed, no user records are assigned this address type and the address type can be deleted. 

To delete an address type:

In the Settings app, select **Users \> Address Types**.  
In the **Address Types** pane, find the address type you want to delete and click the **trash can icon** in the **Actions** column.
In the **Delete Address Type** dialog, click on the **Delete** button. A confirmation message appears and the address type is deleted.

## Settings \> Users \> Departments

Use this setting to configure departments. Departments can be added in the [Extended information](../users/#extended-information) section of a user record. For example, you may want to add departments to reflect library staff or faculty's departments.

### Create a department

1. In the Settings app, select **Users \> Departments**. 
2. In the **Departments** pane, click **New**.
3.  Enter a **Name** for the department in the box.
4.  Enter a department **Code** in the box.
5.  Click **Save**. The department is saved.

### Edit a department

In the Settings app, select **Users \> Departments**. 
In the **Departments** pane, find the department you want to edit and click the **pencil icon** in the **actions** column.
Make your changes to the **Name** or **Code**.
Click **Save**. The department is updated.

### Delete a department

 In the Settings app, select **Users \> Departments**.  
In the **Departments** pane, find the department you want to delete and click the **trash can icon** in the **Actions** column.
In the **Delete Department** dialog, click **Delete**. A confirmation message appears and the department is deleted.

## Settings \> Users \> Custom fields

Use this setting to configure custom fields. Custom fields are used to track additional information in a user record.

### Create a custom field

1.  In the Settings app, select **Users /> Custom fields**.
2. In the **Custom fields** pane, click **New**.
3. In the **Edit custom fields** pane, enter the name of the user record section for the custom field(s) in the **Accordion title** box. 
4. Click **Add custom field** and select the type of field you want to create: **Checkbox**, **Multi-select**, **Radio button set**, **Single select**, **Text area**, or **Text field**.
5. Configure the custom field by checking the box next to **Hidden** and/or **Required*. Add a name for the field in the **Field label** box. Optional: Add text to appear under the information icon in the **Help text** box.
6. In the **Options** section, add a name for the label in the **Option label** box. Select the radio button in the **Default** column to set up the default label. Click the **Add option** button to add the option(s). 
7. Optional: To add additional custom fields, click the **Add custom field** button and repeat steps 2-6.
8. Click **Save & close**. The custom field(s) is/are saved.

### Edit a custom field

1.  In the **Custom fields** pane, click **Edit**.
2.  In the **Edit custom fields** pane, make your changes to the custom field.
3.  Click **Save & close**. The custom field is updated.

### Delete a custom field

Note: Custom fields can be deleted if they are in use, but any information tied to the fields is also deleted.

1.  In the **Custom fields** pane, click **Edit**.
2.  In the **Edit custom fields** pane, click the **trash can icon** next to the custom fields you want to delete. Clear out all of the fields to remove the accordion from appearing in user records.
3.  Click **Save & close**.
4.  In the **Delete field data** dialog, click **Save & lose data**. 

## Settings \> Users \> Owners
 A Fee/fine owner is the agent or office that manages fines for FOLIO transactions. Fee/fine owners collect fees/fines for FOLIO service points.

Libraries may use owners in different ways, such as creating a fee/fine owner for each service point, or creating a fee/fine owner for each library's accounting office, that may collect fee/fines for multiple service points. 

If your library intends to charge any fines, it is important that *every service point* be assigned to a fee/fine owner, even if you do not expect fines to accrue for items associated with that service point. Ensuring that the service point is assigned to an owner will prevent unexpected errors.

When manually creating a fee/fine, Fee/fine owner is a required field.

### Create a fee/fine owner

1.  In the **Fee/fine: Owners** pane, click **New**.
2.  Enter a name for the **Owner** in the box.
3.  Optional: Enter a **Description** about the owner.
4.  Optional: Select the desired **Associated service points**. Note that while a fee/fine owner does not have to have associated service points, you will not be able to use the fee/fine owner in workflows unless it has service points associated with it. 
5.  Click **Save**. The fee/fine owner is saved.

### Edit a fee/fine owner

1.  In the **Fee/fine: Owners** pane, find the owner you want to edit and click the **pencil icon** in the **Actions** column. 
2.  Make your changes to the **Owner**, **Description,** or **Associated service points**.
3.  Click **Save**. The owner is updated.

### Delete a fee/fine owner

1.  In the **Fee/fine: Owners** pane, find the owner you want to delete and click the **trash can icon** in the **Actions** column.
2.  In the **Delete Fee/fine Owner** dialog, click **Delete**. A confirmation message appears and the owner is deleted.

## Settings \> Users \> Manual charges

Use this setting to configure fee/fine types. For example, fee/fine types could be overdue fines, processing fees, or lost item fees. 

When manually creating a fee/fine, **Fee/fine Type** is a required field.

### Create a fee/fine type

1.  In the **Fee/fine: Manual charges** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Optional: Click **Edit** to assign a **Default Charge Notice** and/or **Default Action Notice** to the template and click **Save**.
3.  Click **New**.
4.  Enter a name for the **Fee/Fine Type**.
5.  Optional: Enter the **Default Amount** for the fee/fine.
6.  Optional: Select a **Charge Notice**.
7.  Optional: Select an **Action Notice**.
8.  Click **Save**. The Fee/fine type is saved.

### Edit a fee/fine type

1.  In the **Fee/fine: Manual charges** pane, find the fee/fine type you want to edit and click the **pencil icon** in the **actions** column.
2.  Make your changes to the manual charge.
3.  Click **Save**. The manual charge is updated.

### Delete a fee/fine type

1.  In the **Fee/fine: Manual charges** pane, find the fee/fine type  you want to delete and click the **trash can icon**.
2.  In the **Delete Fee/fine Type** dialog, click **Delete**. A confirmation message appears and the fee/fine type is deleted.

## Settings \> Users \> Waive reasons

Use this setting to configure **Fee/fine: Waive reasons**. 

### Create a waive reason

1.  In the **Fee/fine: Waive reasons** pane, click **New**.
2.  Enter a name for the **Reason** in the box.
3.  Optional: Enter a **Description** about the waive reason.
4.  Click **Save**. The waive reason is saved.

### Edit a waive reason

1.  In the **Fee/fine: Waive reasons** pane, find the waive reason you want to edit and click the **pencil icon** in the **actions** column.
2.  Make your changes to the **Reason** or **Description**.
3.  Click **Save**. The waive reason is updated.

### Delete a waive reason

1.  In the **Fee/fine: Waive reasons** pane, find the waive reason you want to edit and click the **trash can icon** in the **actions** column.
2.  In the **Delete Waive reason** dialog, click **Delete**. A confirmation message appears and the waive reason is deleted.

## Settings \> Users \> Payment methods

Use this setting to configure payment methods. Payment methods are specific to a fee/fine owner. When paying a fee/fine, **Payment method** is a required field.

### Create a payment method

1.  In the **Fee/fine: Payment methods** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Click **New**.
3.  Enter a **Name** for the payment method.
5.  Click **Save**. The payment method is saved.

### Edit a payment method

1.  In the **Fee/fine: Payment methods** pane, find the payment method you want to edit and click the **pencil icon** in the **actions** column.
2.  Update the **Name** as needed. 
3.  Click **Save**. The payment method is updated.

### Delete a payment method

1.  In the **Fee/fine: Payment methods** pane, find the payment method you want to edit and click the **trash can icon**.
2.  In the **Delete Payment method** dialog, click **Delete**. A confirmation message appears and the payment method is deleted.

## Settings \> Users \> Refund reasons

Use this setting to configure refund reasons. When refunding a fee/fine, **Refund reason** is a required field.

### Create a refund reason

1.  In the **Fee/fine: Refund reasons** pane, click **New**.
2.  Enter a **Name** for the refund reason.
3.  Optional: Enter a **Description** about the refund reason.
4.  Click **Save**. The refund reason is saved.

### Edit a refund reason

1.  In the **Fee/fine: Refund reasons** pane, find the refund reason you want to edit and click the **pencil icon** in the **actions** menu.
2.  Make your changes to the **Name** or **Description**.
3.  Click **Save**. The Refund reason is updated.

### Delete a refund reason

1.  In the **Fee/fine: Refund reasons** pane, find the refund reason you want to edit and click the **trash can icon**.
2.  In the **Delete Refund reason** dialog, click **Delete**. A confirmation message appears and the refund reason is deleted.

## Settings \> Users \> Comment required

Use this section to configure whether comments are required when fees/fines are paid, waived, refunded, or transferred. By default, comments are not required.

### Require comment when fee/fine fully/partially paid

To require a comment when a fee/fine is fully or partially paid, under **Require comment when fee/fine fully/partially paid**, select **Yes**. A confirmation message appears and the Require comment setting is saved.

### Require comment when fee/fine fully/partially waived

To require a comment when a fee/fine is fully or partially waived, under **Require comment when fee/fine fully/partially waived**, select **Yes**. A confirmation message appears and the Require comment setting is saved.

### Require comment when fee/fine fully/partially refunded

To require a comment when a fee/fine is fully or partially refunded, under **Require comment when fee/fine fully/partially refunded**, select **Yes**. A confirmation message appears and the Require comment setting is saved.

### Require comment when fee/fine fully/partially transferred

To require a comment when a fee/fine is fully or partially transferred, under **Require comment when fee/fine fully/partially transferred**, select **Yes**. A confirmation message appears and the Require comment setting is saved.

## Settings \> Users \> Transfer accounts

Use this setting to configure available transfer accounts. Transfer accounts are used when your library needs to transfer transactions (for charge or credit) to entities outside of the library. For example, a transfer account may be the bursar's office or a collection agency.

### Create a transfer account

1.  In the **Fee/fine: Transfer accounts** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Click **New**.
3.  Enter a **Name** for the transfer account.
4.  Optional: Enter a **Description** of the transfer account.
5.  Click **Save**. The transfer account is saved.

### Edit a transfer account

1.  In the **Fee/fine: Transfer accounts** pane, find the transfer account you want to edit and click the **pencil icon** in the **actions** column.
2.  Make your changes to the **Name** or **Description**.
3.  Click **Save**. The transfer account is updated.

### Delete a transfer account

1.  In the **Fee/fine: Transfer accounts** pane, find the transfer account you want to edit and click the **trash can icon** in the **actions** column.
2.  In the **Delete Transfer account** dialog, click **Delete**. A confirmation message appears and the transfer account is deleted.

## Settings \> Users \> Transfer criteria

Use this setting to configure the criteria for transferring accounts. For more information about transfer accounts, see [Settings \> Users \> Transfer accounts](#settings–users–transfer-accounts).

### Create transfer criteria

In the **Transfer criteria** pane, select the **Schedule period**.
Add a number to the **Fee/Fines older than (days)** field.
Click the **+** sign to add patron group(s) in the **Patron groups** list.
Select the transfer owner from the **Transfer owner** drop-down list.
Select a transfer account from the **Transfer account** drop-down list.
Select the **Fee/fine owner**.
Add **Transfer type**, **Transfer description**, and **Transfer code** to each **Fee/fine type**.
Click **Save** to save the transfer criteria or click **Run manually** to run a report. 

## Settings \> Users \> Conditions

Automatic patron blocks allow the library to set limits that are automatically enforced. The limits are applied in real time and displayed in the same areas as manual blocks. Patrons can be automatically blocked from checking out, renewing, and/or requesting.

Automatic patron blocks are displayed in the Users app in the Patron blocks section of a user record. Depending on which actions are blocked, the blocks also display in the Check out app after patron barcode entry or patron look-up or if an item barcode is scanned, in the Users app Loans section if you want to renew an item, and in the Requests app after a patron barcode/patron look-up.

The block is automatically removed once the patron falls below the limit.

Note: Conditions and limits have to be in place in order for automated patron blocks to work.

Conditions determine which actions patrons are barred from doing once they hit the limits as outlined for their patron group in [Settings \> Users \> Limits](#settings--users--limits).

These are all the categories for which you can set conditions and limits:

-   Maximum number of items charged out
-   Maximum number of lost items
-   Maximum number of overdue items
-   Maximum number of overdue recalls
-   Maximum outstanding fee/fine balance
-   Recall overdue by maximum number of days

### Configure patron block conditions

1.  In the **Conditions** pane, select the condition you want to configure.
2.  In the selected condition pane, select the action(s) that occur when the defined limits are exceeded: **Block borrowing**, **Block renewals**, and/or **Block requests**.
3.  Enter a **Message to be displayed** (required)
4.  Click **Save**. A confirmation message appears and the patron block condition is saved.

### Edit patron block conditions

1.  In the **Conditions** pane, select the condition you want to edit.
2.  In the selected condition pane, make your changes to the condition.
3.  Click **Save**. A confirmation message appears and the patron block condition is saved.

### Remove patron block conditions

1.  In the **Conditions** pane, select the condition you want to remove.
2.  In the selected condition pane, clear out any blocks and messages.
3.  Click **Save**. A confirmation message appears and the patron block condition is saved.

## Settings \> Users \> Patron Block Templates

Libraries can choose to create templates for use with patron blocks that staff can apply to user records. This allows libraries to have more consistent patron messaging, and can improve reporting.

Patron block templates are created in **Settings \> Users \> Templates**. 

### Create patron block template
1. In the **Patron block templates** pane, select **New** in the top right corner. A **New patron block template** window will open.
2. Enter a **Template name**.
3. Enter a **Block code** (optional). Block codes can be used for reporting or integration purposes. They do not appear in the Users app.
4. Enter a **Description** (optional). This description will only appear when viewing the template in settings.
5. Enter a **Display description** (optional). This appears to staff when applying the block to a particular patron record.
6. Enter a **Message to Patron** (optional). This appears to staff when applying the block to a particular patron record, and can be accessed by discovery layer tools to display to a patron when viewing their library account online.
7. Check the boxes for the appropriate **Block actions** - borrowing, renewals, or requests (optional).
8. Click **Save & close**. The patron block template is saved.

### Edit patron block template.
1. In the **Patron block templates** pane, select the template you wish to edit. It will open for viewing in a fourth pane.
2. Click **Edit** to open the template in edit mode.
3. Make changes as desired.
4. Click **Save & close** to apply changes.

### Delete patron block template
1. In the **Patron block templates** pane, select the template you wish to edit. It will open for viewing in a fourth pane.
2. Click **Edit** to open the template in edit mode.
3. Click **Delete** in the top right.
4. Click **Delete** in the confirmation pop-up.

## Settings \> Users \> Limits

Limits determine the maximum number of materials, recalls, fee/fines, or overdues, that when reached, the conditions you configured in [Settings \> Users \> Conditions](#settings--users--conditions) are applied to a patron's account. Limits are established based on patron groups. See [Settings \> Users \> Patron Groups](#settings–users–patron-groups) for more information about setting up patron groups. 

### Create patron block limits

1.  In the **Limits** pane, select the patron group for which you want to configure limits.
2.  In the selected patron group pane, enter a limit for each category. Leave the field blank if you do not want to set a limit for a certain category.
3.  Click **Save**. A confirmation message appears and the block limits are saved.

### Edit patron block limits

1.  In the **Limits** pane, select the patron group with the limits you want to edit.
2.  In the selected patron group pane, make your changes to the limits.
3.  Click **Save**. A confirmation message appears and the block limits are saved.

### Remove patron block limits

1.  In the **Limits** pane, select the patron group with the limits you want to remove.
2.  In the selected patron group pane, set the limit value(s) to zero to clear out the limit(s).
3. Click **Save**. A confirmation message appears and the block limits are saved.

