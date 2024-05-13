# brother_ppd
Brother .ppd files

Ref. https://help.brother-usa.com/app/answers/detail/a_id/164936/~/how-to-create-a-brother-ppd-file-for-installation---linux

1. Download the **BR-Script driver (Postscript language emulation)**
2. Uncompress and look for file with the printer name and extension **.pp\_**.
3. Use the following command to create a PPD file: **expand filename.pp\_ New filename.ppd**
```cmd
    expand brpml5900dw.pp_ brpml5900dw.ppd
```
