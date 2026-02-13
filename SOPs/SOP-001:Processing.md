## SOP-001:Processing
---
##### Applies to: eBay
##### Version: v1
##### Owner: 
##### Status: Draft 
##### Document Control:
- This document is document-controlled in GitHub. Commit history serves as the official revision record.
--- 
### Purpose: 
- To define how items entering the shop for the first time are identified, recorded, and physically controlled so that no inventory is invisible, duplicated, or untraceable.
- This SOP applies to:
```
- Items newly received into the shop
- Items discovered during cleanup or reorganization
- Items not yet listed on eBay
```
---
### Definitions

##### SKU: 
- A unique 4-digit identifier assigned to an item

##### Location: 
- A stable physical area (e.g., C3-A1 -> Container 3, Shelf A, Row 1)

##### Processing Area: 
- A designated location where new items are evaluated

##### Non-listed item: 
- An item NOT currently Active on eBay

##### Listed item: 
- An item currently Active on eBay

##### InvenTree: 
- System of record for non-listed physical items

##### eBay: System of record for listed items
---
🔹 Step 1: Initial Processing
- While in the Processing Area, items are:
    - Cleaned (if worth it)
    - Decided on:
        - List
        - Hold
        - Scrap
        - Office Use
---
🔹 Step 2: Inventree 
- Recorded in InvenTree
    - SKU
    - Location
    - Status = Not Listed
    - 1–2 reference photos
    - Gets physically tagged w/ SKU
---
🔹 Step 3: List → then move
- Create the eBay listing
- Confirm SKU + item
- Move the item physically
- Update the location and status
    - Option A: Listed items leave InvenTree
         - InvenTree = non-listed physical control only
         - eBay = listed control
    - Option B: Listed items stay in InvenTree
         - Status changes to Listed
         - Used mainly if you want full physical audits
---
##### Rules & Constraints
- No item may be stored without being recorded
- No item may move Locations without a status change record of location
- Draft eBay listings are not used as long-term inventory records
- InvenTree is the source of truth for non-listed items
- eBay is the source of truth for listed items
---
