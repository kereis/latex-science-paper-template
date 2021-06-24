# latex-dhbw-paper-template
Feel free to use this template if you need to write German scientific papers.

## Main file
The main file is called `My_Paper-Max-Mustermann.tex` and is automatically used as the file name of the outcoming PDF file. You can change the name of the TeX file by your choice.

## Style/Package file
All packages that are included via `\RequirePackage` and style settings are located in `style.sty`.

## Git LFS support
LFS support for `*.png` and `*.pdf` files is automatically configured. Make sure your Git host does support LFS and you have Git LFS installed and initialized. Otherwise, if you wish not to use Git LFS, simply remove `.gitattributes`.

## How to build
If you want to build this document "efficiently", you can do that by simply running Arara.

```bash
$ arara -l My_Paper-Max-Mustermann.tex
```

The `-l` parameter is optional and outputs Arara logs into log files.

## Example image
Yes, the example image is Bliss from Windows XP. :P