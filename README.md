# groff-polish-localization
Official Polish localization files for GNU's groff.

Verify your groff version:
```groff --version```
You should get 1.24 or higher. In that release, polish hyphenation rules and macro file has been added.

## Usage
Print sweet looking document on your console:

```groff -k -mm -mpl -Tutf8 example.roff```

Make the same content as PDF file:

```groff -k -mm -mpl -Tpdf example.roff > example.pdf```
