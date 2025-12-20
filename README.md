# groff-polish-localization
Polish localization files for GNU's groff

## Installation
Copy all files from 'groff-polish-localization/tmac' directory into 'groff/<X.YY.ZZ>/tmac/'
(usually groff is located in /usr/share/ folder).

```cd groff-polish-localization```

```sudo cp ./tmac/* /usr/share/groff/1.23.0/tmac/```

## Usage
Print sweet looking document on your console:

```groff -k -mm -mpl -Tutf8 example.roff```

Make the same content as PDF file:

```groff -k -mm -mpl -Tpdf example.roff > example.pdf```
