# Usage

```
python ccdl-win.py -h
python ccdl-win.py -u 6 -l All -x
python ccdl-win.py -u 6 -l en_US -p win64 -x
```

## Installer for standalone product

1. Get old working installer
2. Replace all files and folder in \products
3. Rename \products\\*prefix*-Driver.xml to Driver.xml
4. Check dependency packages are in \products folder (dependencies can be found in Driver.xml)
5. Rename and replace icons in \resources\content\images (96x96.png to appicon.png 122x192.png to appicon2x.png)
6. Run Set-up.exe

## Create manually
1. Extract Set-up zip file (v4 setup not support win10)
2. Download desire package with ccdl-win
3. Rename \products\\*prefix*-Driver.xml to Driver.xml
4. Download packages for installer using installer.py
   ```
   python installer.py
   ```
5. Rename and replace icons in \resources\content\images (from icons folder \*prefix*96x96.png to appicon.png \*prefix*122x192.png to appicon2x.png)
6. Run Set-up.exe
