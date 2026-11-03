# Practical exam files

Text (OCR) copies of the PDFs are in `txt/` (OCR can have small typos; check against the PDF if unsure).

| txt | PDF |
|-----|-----|
| dmv1..dmv4 | `dmv ass 1..4.pdf` |
| dmv5, dmv6 | `DMV Assignment-5.pdf`, `DMV Assignment-6.pdf` |
| ml1..ml6 | `mlass1..6.pdf` |

## View in terminal (no clone needed)

    curl -s https://raw.githubusercontent.com/anandaa-arch/am/main/txt/ml1.txt | less
    curl -s https://raw.githubusercontent.com/anandaa-arch/am/main/txt/ml1.txt | cat

## Copy code into a file

    curl -s https://raw.githubusercontent.com/anandaa-arch/am/main/txt/ml1.txt -o ml1.txt

## Or clone

    git clone https://github.com/anandaa-arch/am.git && cd am && less txt/ml1.txt

## Open the original PDF

    curl -sLO "https://raw.githubusercontent.com/anandaa-arch/am/main/mlass1.pdf"
    open mlass1.pdf        # macOS
    xdg-open mlass1.pdf    # Linux
