# COSTCO AS400 MASTER REFERENCE
**Warehouse Operations · Compiled from all guides · February 2026**

---

## QUICK LOOKUP — ALL COMMANDS A–Z

| Command | Full Name | Category | One-Line Use |
|---|---|---|---|
| ARI | Asset Register Inquiry | Accounting | View equipment on your dept's asset books |
| BDOI | Business Delivery Order Inquiry | Transactions | Research business delivery orders (like EOI) |
| CDCSI | Cost Dept Category Sales Inquiry | Ancillary | View IMU (initial markup %) by dept/category |
| CNI | Canada Ecommerce Order Inquiry | Transactions | Same as EOI for Costco.ca orders |
| COMP | Comparison Analysis | Ancillary | Compare sales across items/depts/years |
| CSR | Category Sales Report | Sales | INP 333 report — category-level sales, enter DEPT |
| DASH | Receiving Dashboard | Merchandising | View and manage receiving appointments |
| DFI | Daily Flash Sales Inquiry | Sales | Flash sales by warehouse (previous day only) |
| DGM | Dept Group Maintenance | Merchandising | Set which depts appear on hot sheet and order |
| DSI | Daily Sales/Inventory Inquiry | Sales | Dept sales and inventory (previous day only) |
| EDMP | Print Daily Maintenance | Merchandising | Print all price-change signs (run after 3am) |
| EDSR | Electronic Data Sign Request | Merchandising | Quick print when item # known, no manual edits |
| EDSM | Custom Sign Maintenance | Merchandising | Customize signs manually or print blank signs |
| EOI | Ecommerce Order Inquiry | Transactions | Research Costco.com orders / check in pickups |
| EPC | Emergency Price Change | Merchandising | Mark down/correct item price for the day |
| EPCI | Price Change Inquiry | Merchandising | View-only: EPCs, downloads, blocked items |
| EPRFD | Profile Inquiry | Passwords | View profiles assigned through EPRFM |
| EPRFM | Profile Maintenance | Passwords | Set up/disable role-based profiles (mgrs only) |
| ESPC | Sign Print Configuration | Merchandising | Configure default settings for EDMP |
| ETINQ | Ecommerce Tire Inquiry | Ancillary | Search SOTO special order tires by order # |
| FCP | Food Court Printer Config | Ancillary | Program item #s to food court pizza printer |
| FFPII | Fresh Foods Period Inventory | Reports | Full department inventory review (Fresh/Meat) |
| FFRII | Reprocessed Items Inquiry | Reports | Track reprocessed/reworked product |
| FSI1 | Financial Statement Inquiry | Accounting | Complete financial statement for dept |
| GLI | General Ledger Inquiry | Accounting | Detailed financial performance by dept # |
| GMD | Gross Margin Dashboard | Accounting | Financial performance for Fresh depts |
| IAD | Item Activity by Dept | Sales | Daily D&D in dollars by department |
| IAFEP | Front End Productivity | Reports | Cashier/SCO productivity stats (not real-time) |
| IAIMV | Dept Salvage Summary | Sales | D&D summary for entire department |
| IAIMI | Inventory Movement Summary | Sales | Stock status by company/region/warehouse/dept |
| IAI | Item Alpha Inquiry | Item Lookup | **Start here** — search items by keyword |
| IATOP | Top Items Report | Merchandising | Top items by sales, refunds, D&D, adjustments |
| IAWD | Warehouse Dashboard | Sales | All major warehouse stats in one place |
| IGM | Item Group Maintenance | Item Lookup | Create/manage item groups for batch reporting |
| IIMN | International Membership Inquiry | Membership | Lookup non-US/CA memberships |
| IOH | Inventory On Hand | Item Lookup | Current on-hand, future arrivals, daily sales |
| IRCI | Instant Rebate Coupon Inquiry | Item Lookup | View active/expired/future IRC coupons |
| ISI | Item Sales Inquiry | Item Lookup | Sales for individual items or groups |
| ISO | Item Sales by Operator | Sales | Sales for an item broken down by cashier |
| ITMG | Item Group Maintenance (User) | Item Lookup | Create user groups for COMP comparisons |
| ITMW | Item Inquiry for Warehouse | Item Lookup | **Most-used detail view** — on-hand, price, today's sales |
| IWS | Weekly Item Unit Sales | Sales | Hourly sales breakdown for item numbers |
| IXI | Item/UPC Cross Reference | Item Lookup | Match item # to all its UPCs |
| KOM | Kiosk Order Maintenance | Transactions | Dept 44 Special Events purchase lookup |
| LSDC | Labor Schedule Door Count | Labor | Enter door counts throughout the day |
| LSDT | Labor Schedule Today | Labor | Check scheduled lanes vs. needed (near real-time) |
| LSCM | Labor Schedule Control File | Labor | Set $/hr, # registers, open/close hours |
| LSIM | Labor Schedule Impact | Labor | Log unusual sales events for future planning |
| LSRM | Labor Schedule Rule Maintenance | Labor | Set dollar caps per dept for forecasting |
| LSSI | Lane and Shift Coverage | Labor | Forecasted vs. scheduled lanes by time |
| LSWM | Labor Schedule Projected Sales | Labor | Enter planned sales to drive scheduling |
| MACR | Merchandise Audit Count List | Reports | On-hand inventory by dept and category |
| MBA9 | Membership Inquiry | Membership | Lookup member info, toggle by name/phone/ID |
| MCI | Manual Check Inquiry | Accounting | View-only: manual checks issued |
| MCE | Manual Check Entry | Accounting | Enter manual checks, coded to G/L accounts |
| IMIN | International Membership Inquiry | Membership | View non-US/CA memberships (view-only) |
| MRC | Membership Report Card | Membership | Membership income dashboard by region/warehouse |
| OUTQ | Print Outqueue | Reports | Manage all print jobs and queues |
| PJI | Purchase Journal Query | Accounting | View which POs have been received |
| PWMI | Password Inquiry | Passwords | View who holds WPM passwords |
| RDPRT | Reroute Printer | Reports | Fix printer issues without Service Desk |
| RHI | Receiving History Inquiry | Item Lookup | Item receiving dates by warehouse |
| RLG | Member Refund Log | Transactions | View refund transactions by warehouse/date |
| ROE | Reorder Entry | Inventory | Reorder product not on auto-reorder |
| RPWD | Reset Role Password | Passwords | Reset a role-based profile password |
| SAST | Sales Audit | Transactions | Find transactions by register, date, type, tender |
| SHC | Sales History by Category | Sales | Historical sales broken down by category |
| SLH | Sales History by Item | Sales | Sales history for a specific item |
| SNI | Serial Number Inquiry | Merchandising | Audit high-end watch movement vs. on-hand |
| SNM | Serial Number Maintenance | Merchandising | Record watch receivings, sales, refunds, RTDs |
| SPOT1 | Special Order Tires Tracking | Ancillary | Status of Tire Center special orders |
| SPI | Supply Purchase Inquiry | Accounting | What supplies were purchased for a dept |
| SPRT | Start Printer | Reports | Restart printer (used with RDPRT) |
| STA | Ecommerce Tire Audit | Ancillary | Status/history of SOTO orders |
| STK | Sales Tracking Inquiry | Sales | **4-week unit sales + D&D — production planning** |
| TAR | Tire Activity Report | Ancillary | All tire sales for depts 22, 87, and Ecom |
| TAXI | Sales Tax Inquiry | Transactions | Member's total sales tax paid previous year |
| TCP | Tire Center Password Maint. | Ancillary | Assign torque/release codes to Tire employees |
| TPR | Tire Center Productivity | Ancillary | Average wait times by region/warehouse |
| TSH | Trash Scan Inquiry | Inventory | Research scan trash entries |
| VA2 | Vendor Appointments at Depot | Receiving | Check if awaited product arrived at depot |
| WAM | Warehouse Ancillary Membership | Membership | Create Gas/Car Wash membership cards |
| WBS9 | Business Membership Inquiry | Membership | Lookup Business Membership info |
| WFBRP | Front End Block Report | Reports | Blocked renewals/voids by cashier (print-only) |
| WII | Warehouse Item Sales Inquiry | Transactions | Member purchase history by member # |
| WIUS | Half-Hour Item Unit Sales | Sales | Half-hour version of IWS |
| WPM | Warehouse Password Maintenance | Passwords | Assign/manage protected program passwords |
| WWPO | Work With Purchase Orders | Ancillary | View open POs — Tire Center tracks incoming tires |

---

## FUNCTION KEYS — UNIVERSAL

| Key | Action |
|---|---|
| **F1** | Help — screen-specific definitions and F-key guide |
| **F3** | Exit — return to previous/main menu |
| **F4** | Search / Prompt — shows available options for the field under cursor |
| **F12** | Cancel — go back one screen |
| **F15** | Shift+F3 — Add to / remove from custom home screen |
| **F18** | Shift+F6 — Toggle between default and custom home screen; jump to bottom of OUTQ |
| **F19** | Shift+F7 — View other outqueues; scroll left in multi-week views |
| **F20** | Shift+F8 — Scroll right in multi-week views |
| **F21** | Shift+F9 — Print |
| **F23** | Shift+F11 — Disable profile (EPRFM); delete item group (IGM) |

> F13–F24 = Shift + F1 through F12. Blue items on screen can be double-clicked.

---

## SIGN-ON CREDENTIALS

### Warehouse (IN) Profiles
| Warehouse # Digits | User | Password |
|---|---|---|
| 1–2 (XX) | WHSEINXX | EDP0XX |
| 3 (XXX) | WHSEINXXX | EDPXXX |
| 4 (XXXX) | WIN0XXXX | EDP0XXXX |

### Membership (MB) Profiles
| Warehouse # Digits | User | Password |
|---|---|---|
| 1–2 (XX) | WHSEMBXX | MEMBER0XX |
| 3 (XXX) | WHSEMBXXX | MEMBERXXX |
| 4 (XXXX) | WMB0XXXX | MBR0XXXX |

### Demo Profiles
- Format: `WXXXDMO` (3-digit) or `WXXXXDMO` (4-digit)
- Password set by user
- Restricted from: EDSM, WII, LSDT, and other sensitive options

> **Never share personal management profiles.** Use generics for general warehouse use.

---

## NAVIGATION TIPS

- **Two sessions at once:** ESC → key `1` next to "Start New Session" → ENTER. Repeat to toggle back.
- **Custom home screen:** Enter any option → F15 to pin it. F18 to toggle between default and custom view.
- **New window:** Options > Rumba+ Desktop Options > Tabs > check "Open Session Profile in new window"
- **Double-click:** Any blue item on screen can be double-clicked. Enable text auto-select: Options > Edit > Double Click Auto Selection (save profile to persist).
- **Numeric keypad:** Use `Field Plus (<+>)` button after entering values; `Field Enter (<ENTER>)` to submit. Some keyboards use right CTRL for Field Enter.

---

## 1 · PASSWORDS

### EPRFM — Assign Role-Based Profiles
**Who:** Staff Managers and above only  
**When to use:** Setting up Optical, Inventory Audit, RTV, Sales Audit, or Vault profiles. Also to disable a profile.

**Steps:**
1. Enter `EPRFM` → F4 for position type list
2. Enter employee number → ENTER
3. F6 to assign user
4. Tab to User Template field → F4 → select template matching employee's role
5. F8 to finalize

**Disable a profile:**  
Enter position type + employee # → ENTER → verify info → F23 → F23 to confirm

> Employees may only have ONE profile. If multi-dept, pick the template that covers the most critical role.  
> After assigning, verify the employee's JTS job code is entered — it auto-triggers Costco U training.

---

### EPRFD — View Assigned Profiles
**When to use:** View-only. See what profiles have been assigned through EPRFM.  
> Full-time sales auditors may ONLY have the Sales Audit profile.

---

### RPWD — Reset Role Password
**Who:** Staff Managers and above  
**When to use:** An employee is locked out of their role-based profile.

**Steps:**
1. Enter the user profile name and reason for reset
2. A temporary password is generated
3. Employee sets their own password on first login

---

### WPM — Warehouse Password Maintenance
**Who:** Assistant Warehouse Managers and Warehouse Managers only  
**When to use:** Adding, changing, or removing passwords for protected programs.

**Steps:**
1. Enter `WPM` → F6 to add new user
2. Enter User ID (max 10 characters) and employee name — **never assign by role, always by name**
3. Employee sets their own password (5–10 characters, letters and/or numbers, no special characters)
4. Assign one or more access types:

| Code | Access | Who Gets It |
|---|---|---|
| APR | Refund Audit | All supervisors and RTV clerks |
| EPC | Emergency Price Change + item downloads + item blocks | Per regional/warehouse manager rules, typically staff mgrs |
| TCP | Tire Center Password | WM, AWM, and Ops Manager ONLY |
| TSH | Trash Scan (remove inventory) | Managers and supervisors; warehouse manager discretion |

> **PWMI** — Use this option to view who currently has each access type.

---

## 2 · ITEM LOOKUP

### IAI — Item Alpha Inquiry ⭐ Start Here
**When to use:** Any time you need to find an item using keywords. The most common starting point.

**Search fields:**
- **Description** — keyword search (e.g., "ribeye", "salmon steak") — most-used field
- **Dept** — combine with description to narrow results (e.g., Dept 14 for water)
- **Location** — defaults to home warehouse; can change to another location #
- **Location Group** — `*NW` = Northwest, `*CN` = Canada, `*STUT` = Utah, etc.
- **Category Code** — further refine within a dept (e.g., TVs in dept 24)
- **Display On Hand** — Y = only items currently in stock; N = includes items previously carried

**From results, key in the Opt column:**
| Key | Takes You To | Use For |
|---|---|---|
| 1 | IA1 — Regional on-hand | Check if nearby warehouse has the item (updates next day) |
| 3 | IIL — Sales by region | Compare performance across warehouses |
| 4 | RHI — Receiving history | See when item was last received |
| 5 | Sign Inquiry | View sign info without printing |
| 6 | Print Sign | Print a sign for the item |
| **8** | **ITMW** | **Detailed item info — most-used drill-down** |
| 0 | HAZMAT info | Disposal information for regulated items |

---

### ITMW — Item Inquiry for Warehouse ⭐ Most Used
**When to use:** Get full detail on a specific item — on-hand count, price, sales, order status.

**What it shows:** Units on hand, department number, sell price, units on order, expected arrival date, NSI (non-saleable inventory), and **today's sales updated in real time** (shows when last updated).

**F-Keys inside ITMW:**
| Key | Action |
|---|---|
| F9 | View any rebates on this item |
| F14 | View applicable taxes |
| F21 | Print a sign from the inquiry screen |
| F22 | View EBT eligibility and environmental fees |

---

### IGM — Item Group Maintenance
**When to use:** Creating or editing groups of item numbers for batch-reporting in ISI or COMP.

**Steps:**
1. Enter warehouse number and group name → ENTER
2. Add or remove item numbers (only active warehouse items can be added)
3. F23 to delete the group

---

### ITMG — Item Group Maintenance (User Groups)
**When to use:** Build personal item groups for use in COMP comparisons (e.g., all CMN donation item numbers).
- F6 to add a new group
- Can link to other user groups

---

### IRCI — Instant Rebate Coupon Inquiry
**When to use:** Finding coupon numbers for IRC adjustments, verifying rebate dates, honoring expired coupons.

**Search filters:**
- Set X next to Active, Expired, or Future
- Expired: must enter a start date
- Future: enter both start AND end date (start date must be future)

**Screen shows:** Item #, full coupon #, IRC amount, quantity limit, start/end dates, units on hand

> **Register entry:** When keying a coupon from IRCI at the register — either **drop the last digit** OR **precede with </>**

---

### ISI — Item Sales Inquiry
**When to use:** View sales data for a specific item or a predefined item group (created in IGM).
- Enter item numbers directly, or enter a group name
- Best used with groups for department-level analysis

---

### IXI — Item/UPC Cross Reference
**When to use:** An item won't scan at the register. Cross-reference the item # to all associated UPCs to verify if the UPC is set up.
- If UPC is found → run an **Item Download via EPC** to push the fix immediately

---

### IOH — Inventory On Hand
**When to use:** Quick view of current on-hand units, future arrivals, and daily sales for an item.
- Enter item number → view snapshot

---

### RHI — Receiving History Inquiry
**When to use:** See when a specific item was last received at a warehouse.
- Enter warehouse # and item number

---

## 3 · TRANSACTION LOOKUP

> **Same-day transactions are NOT available here.** Use the EDP controller for same-day lookups.  
> Shopping history is limited to **10 years** from the original transaction date.

### Shopping History — Privacy Rules (US)
| Who Is Asking | Can We Provide? | Notes |
|---|---|---|
| Member requesting their own history | ✅ Yes | Valid state ID must be verified in person |
| Spouse/household requesting another member's history | ❌ No | Must request their own |
| Business owner requesting affiliate's history | ❌ No | Affiliates must request their own |

> Never turn the screen toward a member. All requests must be made in person by the individual whose information it is.

---

### WII — Warehouse Item Sales Inquiry ⭐
**When to use:** Look up a member's purchase history. Includes refunds and department rings.

**Requirements:** Member # AND (Dept # or Item #) — both sides are mandatory.

**Steps:**
1. Enter member #, dept or item #, and date range → ENTER
2. Refunds show as **negative** in Ext Sell Price column
3. F11 = Fold — adds item description (use when you don't have the item #)
4. F21 = Print the transaction
5. White-highlighted items = had an IRC at purchase → press ENTER to see coupon detail

---

### EOI / CNI — Ecommerce Order Inquiry
**When to use:** Research a Costco.com (EOI) or Costco.ca (CNI) order, or check in an online order pickup.

**Search by:** Order # (9–10 digits) or Bill to Membership #

**Order detail screen shows:** All items, order #, membership #, order date, and total.

**Drill into an item:** Key `5` or `X` next to the item → see individual price, S&H, delivery fees, tax, and coupon amount

> On Ecom, coupons are treated as **tender** — they appear in item detail, not as a separate refund line.

---

### BDOI — Business Delivery Order Inquiry
**When to use:** Research orders fulfilled through business delivery (same workflow as EOI).
- Search by order # or membership #
- Key `5` or `X` to drill into item detail
- F14 = payment method | F19 = view refunds

---

### KOM — Kiosk Order Maintenance
**When to use:** Refunds for Dept 44 (Special Events) when the vendor picked up merchandise and the member has nothing to return physically.

**Search by:** Order #, membership #, phone #, item #, or warehouse #

---

### RLG — Member Refund Log
**When to use:** Research refund transactions for a specific warehouse and date.

**Defaults:** Home warehouse, previous day (both can be changed)
- Y in Dept Ring column = refund was processed as a dept ring
- \* = dept ring converted to an inline item
- Key `X` next to operator # to see full refund detail

> Tracking number column only appears when NOT viewing same-day data.

---

### SAST — Sales Audit
**When to use:** Find transactions on a specific register for a date range. Filter by transaction type or tender type. Also reachable from inside WII.

**Steps:**
1. Set date range and desired filters → ENTER
2. TAB to a transaction → Field ENTER to drill in
3. Items are grouped by dept/item # (NOT in scan order)

> For exact scan sequence, use the EDP controller.

---

### TAXI — Sales Tax Inquiry
**When to use:** A member wants to know how much sales tax they paid in the previous calendar year (for federal tax deduction purposes, certain states only).
- Enter member # and year → displays total annual sales tax paid

---

## 4 · MERCHANDISING

### EDSR — Electronic Data Sign Request
**When to use:** You know the item # and just need to print a sign with no manual changes.

**Steps:**
1. Enter `EDSR` → select sign size (M = medium, L = large are most common)
2. Enter up to 45 item numbers or UPCs
3. F21 (Shift+F9) to print
4. Printer 1 = main sign printer | Printer 2 = mobile sign printer

---

### EDMP — Print Daily Maintenance ⭐
**When to use:** Print all signs that need updating due to buyer price changes. **Do this every morning.**

**IMPORTANT: Run AFTER 3:00am** — EDMP updates daily at 3:00am local time.

**Steps:**
1. Enter `EDMP` after 3:00am
2. Set filter (on-hand items or price changes) and date — change date for holiday pre-planning
3. Set Print = Y, choose size (default M)
4. F21 → auto-sends to sign printer 1

> **Signs MUST be printed and hung before opening every day.**

---

### ESPC — Sign Print Configuration
**When to use:** Changing default dept sign sizes or which depts auto-print with daily maintenance.
- F10 (Change) to adjust settings

---

### EDSM — Custom Sign Maintenance
**When to use:** Printing a customized sign that doesn't match the current data — "Last One Display," a price/description correction, or before the daily download runs.

**Steps:**
1. Enter item #, size, quantity → edit any field → exit with F3 (signs print on exit)
2. Leave item # blank with size + qty filled in → prints a blank free-form sign

> If you manually change the sell price, the per-oz/per-bottle unit price will NOT auto-update — calculate and enter it manually.

---

### EPC — Emergency Price Change
**Who:** Typically limited to staff managers. Access set in WPM.  
**When to use:** Marking down an item or correcting a register price for the current day.

**Steps:**
1. Enter `EPC` → enter User ID and password
2. List of today's price changes appears
3. F6 to add a new EPC → enter item #, new price, reason → ENTER

**Copying from a previous day:**
- Change the date in EPC → key `3` next to the EPC to copy it to today

**Important:** To restore an item's original price after an EPC, you **must run an Item Download** — you cannot reset it with another EPC.

---

### Item Download (via EPC)
**When to use:**
- Register price doesn't match AS400
- Buyer added a fee or link to an item mid-day
- Restoring original price after an EPC

**Steps:**
1. In EPC → F15 to access Item Downloads
2. Enter required fields → F8 to update

---

### EPCI — Price Change Inquiry
**When to use:** View-only. Check if an EPC, item download, or block has been entered on an item.

---

### Blocked Items (via EPC)
**When to use:** Preventing an item from selling at the register (recalls, item # changes).

**In EPC → F18** to view current blocked items:
- K = requires key flick | P = completely prohibited from sale

**Add a block:** F6 → enter K or P → enter reason  
**Remove a block:** Key `D` next to the item

> If a register shows "NOT FOR SALE," check EPC for an active block.

---

### SNM — Serial Number Maintenance
**When to use:** Logging any movement of high-end watches (receiving, sale, refund, RTD shipment). Replaced the Watch Tracking Log.
- Enter transaction code → item #, serial #, or membership #
- **All watch movement must be recorded here**

---

### SNI — Serial Number Inquiry
**When to use:** Auditing watch movement. Finding discrepancies between SNM records and actual on-hand.
- Discrepancy View = most common

---

### IATOP — Top Items Report
**When to use:** Research top sellers, top D&D, top refunds, or top markdowns for a warehouse or department.

**Steps:**
1. Leave Dept blank for all depts; enter dept # to drill into one department
2. Default = top 10 results (adjustable)
3. Add Category Code + Dept for specific sub-sets (e.g., top TVs in dept 24)
4. F19/F20 = compare ranks and items between two warehouses or regions

---

### DASH — Receiving Dashboard
**When to use:** View and process receiving appointments. Primarily used by Receiving — but any dept can check their incoming inventory here.

---

### DGM — Department Group Maintenance
**When to use:** Configure which departments appear on the hot sheet and the order they print.
- Sequence 1 prints first | 0 removes from hot sheet

---

## 5 · WAREHOUSE SALES

### STK — Sales Tracking Inquiry ⭐ Meat/Fresh Planning Tool
**When to use:** Planning daily production quantities. Shows exactly how much was sold and destroyed each day over the past 4 weeks for any department.

**Steps:**
1. Enter fiscal year, period, and week
2. Enter location (or location group) and department number
3. Results show units sold + D&D per day for a 4-week window
4. F19/F20 = scroll left/right through weeks
5. F21 = print full report
6. F22 = export to Excel

> **Meat department:** This is your primary production planning tool. Use weekly to dial in how much to cut each day.

---

### DSI — Daily Sales/Inventory Inquiry
**When to use:** View a department's sales and inventory numbers. **Previous day only — not real-time.**

- **View by Warehouse:** See every dept for one location (daily, weekly, period, YTD)
- **View by Dept:** See all locations for one department — great for benchmarking against neighboring warehouses

---

### DFI — Daily Flash Sales Inquiry
**When to use:** Quick flash summary of sales by warehouse for the previous day. Daily, weekly, period, and YTD totals.

---

### ISO — Item Sales by Operator
**When to use:** View how many units of a specific item each cashier sold within a date range.
- Enter warehouse # and item # → shows operator #, units sold, and dollars

---

### IAWD — Warehouse Dashboard
**When to use:** One-stop view of all major warehouse metrics. **NOT same-day.**

| View Code | Content |
|---|---|
| 00 | Main — major warehouse stats (default) |
| 01 | Inventory — on-hand and dept sales YOY |
| 02 | Sales — all depts, comp vs. last year by dept |
| 03 | Front End Productivity (simplified IAFEP) |

---

### IAIMI — Inventory Movement Summary
**When to use:** Stock status summary at company, region, warehouse, or dept level.
- Select an item + F15 (Sales/UPC) → see hand-keyed count vs. each individual UPC scan count

---

### IAIMV — Department Salvage Summary
**When to use:** View D&D (damaged and destroyed) summary for an entire department.
- Enter warehouse #, dept #, and time frame

---

### IAD — Item Activity by Department
**When to use:** Detailed daily D&D in dollars for each item in a department.
- Shows net landing cost, sell cost, and total per item

---

### IWS — Weekly Item Unit Sales
**When to use:** Hourly sales breakdown for specific items on a given day.
- Enter warehouse #, item #, time frame
- Page Down for multiple items

---

### WIUS — Half-Hour Item Unit Sales
**When to use:** Same as IWS but in 30-minute intervals — more granular production planning.
- Enter warehouse #, item #, time frame

---

### SHC — Sales History by Category
**When to use:** Historical sales broken down by category code within a department.
- Enter dept #, warehouse #, time frame
- Enter category (F5 for Category Inquiry)
- F4 to break down into weekly sales

---

### SLH — Sales History by Item
**When to use:** Sales history for a specific item.
- Enter warehouse #, time frame, item number
- F4 to break into weekly view

---

### IIL — Item Sales by Warehouse (from IAI option 3)
**When to use:** See how a specific item performs across all warehouses in a state or region. Commonly used for focus items (stamps, movie tickets) to see how warehouses rank.
- Enter item # → enter state abbreviation or region code

---

## 6 · LABOR SCHEDULING

### LSDT — Labor Schedule Today ⭐ Front End Daily Tool
**When to use:** Real-time check of how many lanes are open vs. how many are scheduled vs. how many are needed based on sales.

**Available to:** All AS400 users. Home warehouse only.

| Column | Meaning |
|---|---|
| Actl Lane | Registers currently open |
| Sched Lane | Lanes on the schedule (based on cashier count) |
| Hrly Actual Sale | Real sales from Front End registers |
| Hrly Plan Sale | Planned hourly sales from LSWM |
| Sls Diff | Cumulative actual minus cumulative planned |

Intervals: 15, 30, or 60 minutes (adjustable)

---

### LSCM — Labor Schedule Control File
**Who:** Staff Managers and above, plus Front End profiles  
**When to use:** Setting the foundational scheduling parameters — $/labor hour, number of registers, opening and closing hours.

- **Update for holidays** to reflect early or extended hours before the holiday week

---

### LSWM — Enter Projected Sales
**Who:** GMs, AGMs, FRNs, ADMs  
**When to use:** Entering planned sales dollars for each day to drive recommended scheduled hours.

- Red # in "Imp Flg" = large purchase impacted prior year's sales that day
- **Holiday closures (Christmas Eve, New Year's Eve):**
  1. Key `6` next to the date → change "Select a Plan" to `3`
  2. Change the selected date to the PRIOR YEAR's equivalent date

---

### LSDC — Door Count Entry
**When to use:** Logging actual door count throughout the day so Front End supervisors can see the real traffic load.

---

### LSIM — Sales Impact Entry
**When to use:** Recording unusually large or unusual sales events so they factor properly into NEXT YEAR's planning.
- F6 to add → enter reason and dollar amount
- Auto-logged (no entry needed): resale, refunds, kiosk orders, gasoline, jewelry, special events, coupons

---

### LSRM — Labor Schedule Rule Maintenance
**When to use:** Prevent large single transactions (e.g., a $50,000 resale order) from artificially inflating the lane forecast.
- Set a dollar cap per department — transactions exceeding it are excluded from forecasting
- These dollars still show correctly in LSDT and LSWT

---

### LSSI — Lane and Shift Coverage
**When to use:** View the system's forecasted lanes needed vs. what's actually scheduled for any given day and time.
> The system counts ALL Service Clerks as cashiers when calculating recommended lanes.

---

## 7 · MEMBERSHIP

### MBA9 — Membership Inquiry
**When to use:** Quickly look up a member's info, find a membership number, or view forecasted renewal fees.

**Toggle search modes with F11:** Member #, Last/First Name, "sounds like" name, ID type and #, 7-digit phone, mailing address

- Once found: F4 → action code prompt

---

### WBS9 — Business Membership Inquiry
**When to use:** Same as MBA9 but for Business Memberships.
- F11 to toggle: business name, 7-digit phone, business address
- F4 → action code prompt

---

### IMIN — International Membership Inquiry
**When to use:** View membership info for a member outside the US and Canada.
- Requires membership # AND country of issuance
- View-only. Very limited display. No changes allowed.

---

### MRC — Membership Report Card
**When to use:** Viewing membership income performance dashboard.
- Filter by company, region/state, or warehouse
- Shows this year vs. last year and % change by date, period, and YTD
- F11 = toggle to Captured Renewal Rate and Renewal Trend

---

### WAM — Warehouse Ancillary Membership
**When to use:** Creating membership cards for the Gas Station or Car Wash.
1. Enter `1` in the Gas/Car Wash Attendant field before entering WAM
2. F4 for action code prompts

> Refer to the "Non-Member Membership Cards – Ancillary Cards" job aid for full steps.

---

## 8 · ACCOUNTING & FINANCIAL

### MCE — Manual Check Entry
**When to use:** Entering any manual check issued from the warehouse to track and communicate with central accounting.
- All checks must be coded to a specific G/L account
- F12 = Display G/L Accounts to look up account codes

---

### MCI — Manual Check Inquiry
**When to use:** View-only lookup of manual check records.

---

### GMD — Gross Margin Dashboard
**When to use:** View detailed financial performance for Fresh departments (Meat, Bakery, Deli, etc.).
- Enter warehouse # and dept #
- Page Down for last year's performance

---

### FSI1 — Financial Statement Inquiry
**When to use:** Complete financial statement for a department.
1. Enter `1` for company → enter period → press X next to any sub-account to expand

---

### PJI — Purchase Journal Query
**When to use:** See which POs have been received for a dept within a time frame.
- Enter warehouse #, dept #, time frame

---

### SPI — Supply Purchase Inquiry
**When to use:** See what supplies were purchased for a specific department (chemicals, bags, etc.).
- Enter warehouse # and time frame
- Key `1` next to an account for item-by-item view
- Key `1` next to a day for daily breakdown

---

### ARI — Asset Register Inquiry
**When to use:** View what equipment is on your department's asset register.
- Enter warehouse # and dept #

---

### GLI — General Ledger Inquiry
**When to use:** Detailed financial performance report.
- Enter dept # → full G/L breakdown

---

## 9 · REPORTS

### IAFEP — Front End Productivity Report
**When to use:** Reviewing cashier and Self-Checkout performance stats. **NOT real-time — current day not available.**

- Enter warehouse # to drill into a location
- F19/F20 to toggle views: Main → Data Screen → Time Screen
- **Self-Checkout:** Enter Y in the Self-Checkout field before drilling in
- **F1** inside IAFEP = detailed definitions of every metric and how it's calculated

---

### WFBRP — Warehouse Front End Block Report
**When to use:** Review blocked renewals, voids, FE signups, and member #99 by cashier ID.
> **This report can ONLY be viewed by printing — it is not accessible on-screen via AS400.**

---

### MACR — Merchandise Audit Count List
**When to use:** Generate on-hand inventory report for a specific dept and/or category.
- Enter dept → optionally add category code to filter
- Shows: item #, description, category, on-hand, NSI on-hand

---

### FFPII — Fresh Foods Period End Inventory Review
**When to use:** Complete inventory snapshot for a Fresh or Meat department at the end of a fiscal period.
- Enter warehouse # and dept #
- Page Up and Down to review all items

---

### FFRII — Reprocessed Items Inquiry
**When to use:** Track items that have been reprocessed or reworked within the department.

---

### OUTQ — Print Outqueue
**When to use:** Manage print jobs for any printer in the warehouse.

| Key in Opt | Action |
|---|---|
| 2 | Change — move printer, adjust copies, change start page |
| 4 | Delete — **cannot be undone** |
| 5 | Display — view report without printing |
| 6 | Release — send to printer |

**Navigation:**
- F19 (Shift+F7) = view/switch outqueues
- F18 (Shift+F6) = jump to bottom (newest jobs)
- SOUTQ = sign-specific outqueue (sign jobs delete after printing)

**Rerouting to main office printer:** In the Change screen, remove the suffix from the outqueue name (e.g., change `PRINT110RC` to `PRINT110`) → key `6` to release.

> Main printer name format: `PRINT[location#]` (e.g., PRINT110). The main report printer name is `PRINTLOC`.

---

### RDPRT / SPRT — Reroute or Reset Printer
**When to use:** Printer issues — fix without calling the Service Desk.

**Reroute Printer 1 → Printer 2:**
1. RDPRT → key `1` next to Source Printer (Printer 1)
2. Key `1` next to Destination Printer (Printer 2)
3. Confirm reroute message
4. SPRT → restart Printer 1
5. Send a test print

**Reset Printer (undo last reroute):**
1. RDPRT → key `6` next to Source Printer
2. SPRT → restart
3. Send a test print

> Reset only undoes ONE reroute. For multiple reroutes, call the Service Desk.

---

## 10 · INVENTORY & RECEIVING

### TSH — Trash Scan Inquiry
**When to use:** Research entries made in the RF Scanner option 72 (Scan Trash).

---

### ROE — Reorder Entry
**When to use:** Place a reorder for a product that is NOT on auto-reorder.
- Enter dept → key reorder for the specific item

---

### VA2 — Vendor Appointments at Depot
**When to use:** Check whether your awaited product has arrived at the depot yet.
- Enter region # and dept #
- Shows time in yard, time in receiving — great for tracking inbound product status

---

### DASH — Receiving Dashboard
(Also listed under Merchandising)  
**When to use:** View all receiving appointments and their status. Primarily Receiving dept, but useful for any dept checking on incoming inventory.

---

## 11 · ANCILLARY

### FCP — Food Court Printer Config
**When to use:** Programming which item numbers route to the Food Court kitchen printer (pizza sales).
- F22 to delete items no longer in use

---

### CDCSI — Cost Dept Category Sales Inquiry
**When to use:** View initial markup percent (IMU) and margin components by location, dept, and category.

---

### COMP — Comparison Analysis
**When to use:** Compare sales history across items, item groups, departments, vendors, locations, or date ranges for the last 3 fiscal years.

---

### TCP — Tire Center Password Maintenance
**Who:** WM, AWM, and Ops Manager only. Must be assigned in WPM first.  
**When to use:** Assigning torque/release codes ("torque codes") that confirm a vehicle's service is complete.

**Steps:**
1. Enter employee # → F6
2. Enter name → employee sets their password → F8
3. F4 from main screen = view all active employees
4. F10 = delete an employee

---

### TPR — Tire Center Productivity Report
**When to use:** View average wait times by company, region, or warehouse.

---

### TAR — Tire Activity Report
**When to use:** All tire sales for departments 22, 87, and Ecommerce.
- Key `1` next to a region to drill to warehouse level
- Use F-Key prompts at bottom for additional views

---

### ETINQ — Ecommerce Tire Inquiry
**When to use:** Look up a Special Order Tires Online (SOTO) order by Ecommerce order number.
- F4 if order # is unknown

---

### STA — Ecommerce Tire Audit
**When to use:** View status and full history of any SOTO order.
- Multiple filter options (cannot combine)
- White font on item # = comments exist

---

### SPOT1 — Special Order Tires Tracking
**When to use:** Track the status of Tire Center special orders.

---

### WWPO — Work With Purchase Orders
**When to use:** View open POs, standard distributions, auto-distributions, and transfer requests. Tire Center uses this to track incoming tires.

| View | Content |
|---|---|
| 1 | Summary View |
| 2 | Status View |
| 3 | Item View |
| 4 | Freight/Budgeting View |

---

### Inventory Options (Ancillary Depts)
Ancillary departments (Tire, Optical, Hearing, etc.) count inventory on the **first day of each fiscal period**.
- Refer to: **AS400 Options for Fresh Foods Inventory** guide (on Inventory Audit page of Warehouse Operations)
- RF Scanner option 63 = FFI (Fresh Foods Inventory — input counts)

---

## 12 · RF SCANNER OPTIONS

RF scanners provide wireless AS400 access with barcode scanning capability. Most commonly used options:

| Option | Name | How To Use |
|---|---|---|
| **07** | Print Depot Labels | Select printer (1=RCV, 2=RTV), enter text in any field, enter # of tags → print |
| **11** | Item Inquiry ⭐ | Scan barcode or enter item # → view dept and all on-hand quantity columns |
| **13** | Item Alpha Inquiry | Enter description (min 3 chars) and/or dept → search results |
| **16** | UPC Inquiry | Scan or key UPC → displays item description and item number |
| **18** | Item Sales Report | Enter warehouse # and optional date, scan/key all items, F21 to print |
| **19** | Item Group Maintenance | F4 to scan/key items; F10 to review list; key 4 to remove an item |
| **20** | Merchandise Audit Entry | Scan or key counts for inventory audit; multiple counts per item allowed |
| **21** | Clear Audit Count List | Clears all counts entered in option 20 |
| **22** | Print Merchandise Audit Report | Prints the counts from option 20 (same report as MADR) |
| **23** | EDP Sign Requests | Enter size letter; scan items; F10 to review; F21 to print; select printer |
| **36** | Print Pallet Tag | Select printer; enter item/UPC; enter qty; optional PO # and initials → ENTER |
| **72** | Scan Trash ⭐ | Requires WPM username/password. Scan or key damaged/waste items to remove from inventory |
| **88** | Item/UPC Cross Reference | Same as IXI — match item # to all associated UPCs |
| **98** | Item/UPC Check | View item description, item #, UPC, sell price, and per-unit pricing for multipacks |

### RF 72 — Scan Trash: Important Notes
- **Reverse same-day entry:** Enter a negative amount in the Sell Unit field
- **Reverse older entry:** Use RTV option NSE18
- **Research past entries:** Use AS400 option TSH

---

## MEAT DEPARTMENT — MOST-USED COMMANDS

| Command | Daily Use Case |
|---|---|
| **STK** | Plan production for each sub-dept — pull 4 weeks of sales + D&D for your dept |
| **ITMW** | Quick check on a specific item's current on-hand before cutting |
| **IAI** | Find any item by keyword — start here for all item questions |
| **IRCI** | Find coupon # for a customer adjustment; verify active/expired IRC dates |
| **WII** | Member says they bought something here — look up their purchase history |
| **RLG** | Review all refunds processed for the day |
| **EDMP** | Print daily price-change signs every morning before open |
| **EDSM** | Make a custom sign for last ones, display items, or same-day corrections |
| **IAD** | See today's D&D dollars by item (check against your records) |
| **IAIMV** | Full dept D&D summary for a period |
| **FFPII** | End-of-period inventory review for the department |
| **VA2** | Check whether your depot product has arrived yet |
| **RF 11** | Fastest item lookup on the floor — scan a barcode and see on-hand immediately |
| **RF 72** | Write off damaged/expired product from inventory |

---

## COMMON SCENARIOS — QUICK ANSWERS

**An item won't scan at the register:**
→ IXI (or RF 88) to verify the UPC is set up → if yes, run an Item Download via EPC

**Need to check how much we have of an item:**
→ ITMW (enter item #) — shows on-hand, on-order, and today's real-time sales

**Member wants their shopping history:**
→ Verify state ID in person → WII with member # + dept or item #

**Need to plan how much ribeye to cut tomorrow:**
→ STK with your dept # — pull last 4 weeks of daily units sold and D&D

**Price on the shelf doesn't match the register:**
→ EPC to correct price → run Item Download (F15 in EPC) to push it to registers

**Sign needs to go up today but the system hasn't updated yet:**
→ EDSM to manually create or edit the sign

**Product not scanning — need to check coupon:**
→ IRCI with the item # to find the active coupon number

**Printer is stuck or jammed:**
→ OUTQ to view/delete stuck jobs → RDPRT to reroute → SPRT to restart printer

---

*Compiled from: AS400 Guide (Feb 2026), AS400 Command Sheet, AS400 Reference Guide | Warehouse Operations*
