# Fix Microsoft Office License Errors in Minutes
Seeing license errors like "Product activation failed"? Try this:
1. Open Command Prompt as administrator.
2. Navigate to the Office directory:
```
cd "C:\Program Files\Microsoft Office\Office16"
```
3. Run this to rearm:
```
cscript ospp.vbs /rearm
```
4. Restart your computer.
If that doesn't help, try:
```
cscript ospp.vbs /act
```
> **Reminder:** Keep your Office and Windows updated to avoid future activation issues.
---