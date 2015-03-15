This is just a reformatted version of the FCC decision "Promoting an Open Internet" that can be read on a kindle or similar epub/mobi device. Please enjoy responsibly and do not rely on the document for anything important. 
  



# TODO

1. Generate mobi

2. Latex format for better printing. 

# Conversion 

The majority of the conversion was done by the following pandoc invocations. I used a little sed and elbow grease for the remaining tweaks. 

    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A1.md --id-prefix=fcc         FCC-15-24A1.docx
    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A2.md --id-prefix=wheeler     FCC-15-24A2.docx
    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A3.md --id-prefix=clayburn    FCC-15-24A3.docx
    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A4.md --id-prefix=rosenworcel FCC-15-24A4.docx
    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A5.md --id-prefix=pai         FCC-15-24A5.docx
    pandoc --atx-headers  -f docx -t markdown-raw_html -s -S -o FCC-15-24A6.md --id-prefix=oreilly     FCC-15-24A6.docx


