# Compliance Checklist

## Answering the question: **Is this done?**

**Purpose**

Everyday there are compliance items that managers and supervisors want to know are completed correctly. Compliance checklist allows managers to see as items on a repeatable checklist are completed. 

There are two components to **Compliance Checklist**

1. Checklist Items
2. Checklists

## Checklist item

A **Checklist Item** is an item that can be completed.
It is either complete, or incomplete. 

When a checklist item is marked 'Complete' the following information is stored: 
* Name of the person who completed the item
* Date and time the item was completed

A **Checklist Item** is like writting down a task on a single sticky note. 

Every single **Checklist Item** belongs on a **Checklist**.
There are no **Checklist Items** that appear outside of a checklist. 

## Checklist

A **Checklist** is a 'page' of **Checklist Items**.
This is kind of like an airplane pilot's checklist or a repeating todo list that you might have. 

A **Checklist** is generated from a **Checklist Template**. The **Checklist Template** is a 'cookie-cutter' of all of the items that should appear on a new checklist. 

A checklist generally will only be considered complete when all of the **Checklist Items** that make up the list can be completed.

#### Examples of Checklist
* Some business units have 'shift-duties' lists which are a repeating checklist of things that might be done.
* A cleaning checklist for a building or area could be a checklist
* A vehicle walk-around could be a checklist that is completed regularly.  


## Considerations and TODOs
1. Should it be possible to complete a checklist if all of the items on the checklist haven't been completed? 
    * Do we need to have a special warning for the user when this happens? 
2. What happens when you add a new **Checklist Item** to a **Checklist Template**?  Possible actions are: 
    * The additional checklist item is only seen on new Checklists when they are created. 
    * The additional checklist item is added to all currently open checklists that were generated from that template. 
    * The user is asked whether they want to add the item to all currently open checklists which were generated from that template. 
    * [It is assumed] that we would not add the new checklist item to finished or closed checklists. 
3. Is it possible to check a Checklist Item, but then un-check it again? (For example if you realize that it wasn't actually done.)
    * What are the implications for closing a Checklist?
4. Is it possible to re-open a checklist that has been closed? Under what circumstances?
    * You would have to have at least one unchecked item.