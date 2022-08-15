# LVIC-WMS
 Inventory and shipping management system

## File/data manipulation

1. Open a CSV/Excel file
2. Group each line by SO# ⇒ then by received status
3. Cross-check SO# with list of ongoing Integration projects
    1. Create 2 files/reports 
        1. If not integration project:
            1. Separate complete orders with orders that have outstanding orders
            2. List of orders in transit with relevant tracking info
        2. Is integration project:
            1. list projects still missing items
            2. Group by Customer ⇒ then project (Final destination)
4. Send reports via email to myself

## Automation

1. Daily pull Warehouse Tracking Search: Results ***or*** extract file form email auto sent by NetSuite
2. Input to above
3. Be able to write information to NetSuite Tracker and update NetSuite

## Web App

1. Django/Flask? to create front-end web app
2. Create accounts for warehouse team
3. Be able to have pages for each SO# with details of order
4. Integration projects show progress and other relevant info for project and link to resource pages
5. Be able to upload relevant documents for each So#
6. Be able to group SO#s into single project
7. Deploy/host via public cloud
