This is an academic CV template using KOMA-script and with XeTeX support.

The [KOMA script](https://www.ctan.org/pkg/koma-script?lang=en) implementation allows for quick changes to personal tastes and requirements. It is intended to be compiled on XeTeX which allows the use modern professional fonts. The only requirement is that the serif font has _small caps_, like Linux Libertine that is used in the example (available [here](http://www.linuxlibertine.org/index.php?id=2&L=1)). The sans-serif font in the example, Myriad Pro as well as the used CJK (Chinese-Japanese-Korean) font, Lantinghei SC Extralight, should come installed on any modern macOS computer. Note that a CJK font is not required if no alternative CJK name is provided.

When hyperlinks and bookmarks are disabled, the template satisfies the PDF/X-3:2003 standard ([ISO 15930-6](https://www.iso.org/standard/39940.html)). A proof of verification of the example is shown in the ```CVtemplate_nolinks_ISO_compliance.pdf```.

For the ISO support you need to use the ```\ISOtrue``` line and comment-out the ```\ISOfalse```. Then, compile the file with 
```
xelatex myfile.tex -output-driver="xdvipdfmx -V 3"
```

Plug-and-play Biblatex support might be added in the future.
