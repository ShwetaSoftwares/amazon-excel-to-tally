AMAZON E-Commerce

Amazon Sales files
==================
1. Vouchers-GST-Sales-Amazon.xls (Contains the Amazon Sales data)
2. Vouchers-GST-Sales-Amazon-xml-tags.xml (Supporting / mapping file - Don't change it)
3. Vouchers-GST-Sales-Amazon-macro.txt (Supporting / mapping file - Don't change it)

Steps to Import data into Tally
===============================
1. Create a Company or Open an existing Company
2. Start udiMagic
3. Select option "Excel to Tally"
4. Select option "Import data into Tally"
5. Select the following files :
  Excel file : Vouchers-GST-Sales-Amazon.xls
  XML file   : Vouchers-GST-Sales-Amazon-xml-tags.xml
  
  PS: You must enable / tick the option "Use separate file for XML tags" to select the XML tags file.
  
6. Click the option "Start" to import the data into Tally.


Other files (Used for mapping)
==================================
1. Vouchers-V10-Sales-Purchase-With-Stockitems-Advanced.xls
This is the STANDARD Excel template with which the Amazon file viz Vouchers-GST-Sales-Amazon.xls is mapped.

2. Vouchers-V10-Sales-Purchase-With-Stockitems-Advanced-xml-tags.xml
This is the supporting file for the STANDARD template.

IMPORTANT NOTEs
===============
1. The Party ledger name is fixed as "Amazon India" with following details :
a. State : Karnataka
b. GSTIN : 29AAICA3918J1ZE

2. If you want to have a different Party Ledger name in Tally say "Amazon India Pvt Ltd", then add simply as Alias to it as "Amazon India".

3. You must manually modify the Party Ledger "Amazon India" and set the "Is E-Commerce operator" to YES under the GST features. If you do NOT do this, all the entries will be shown as B2B (as Tally will treat the GSTIN of Amazon India as the GSTIN)
