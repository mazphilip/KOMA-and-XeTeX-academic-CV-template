This is an academic CV template using KOMA-script and XeTeX support.

The [KOMA script](https://www.ctan.org/pkg/koma-script?lang=en) implementation allows for quick changes to personal tastes and requirements. It is intended to be compiled on XeTeX which allows the use modern professional fonts.

When hyperlinks are disabled, the template is intended to satisfy the PDF/X-3:2003 standard ([ISO 15930-6](https://www.iso.org/standard/39940.html)).

For the ISO support you need to use the ```\ISOtrue``` line and comment-out the ```\ISOfalse```. Then, compile the file with 
```
xelatex myfile.tex -output-driver="xdvipdfmx -V 3"
```
