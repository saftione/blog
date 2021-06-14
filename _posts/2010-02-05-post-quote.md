---
title: "Excel-Template for Serial-COM-Interface"
categories:
  - Blog
tags:
  - Technical
  - Research
---

Excel sheet to enter the serial interface of scales/analyzers in Excel

<a href="https://www.opendesktop.org/p/1012532/" class="btn" target="_blank">Download from gnome-look</a>


Change Excel settings from „,“ to „.“.
„File„
„Options„
„Advanced„
Remove check mark from „Take over separator from operating system„
change from „,“ to „.“
Enter the COM Port of the scale (displayed in the device manager)
Check if the COM Settings match the settings of the balance.
In the Excel sheet „Worksheet“, the values are entered in the current cell when the data are transferred (e.g. by pressing the print key on the scale).
The transferred letters and blanks can be removed with „Replace„.
With „Save to CSV“ a backup loop is started which saves the range I16 to J499 every 5 minutes.
