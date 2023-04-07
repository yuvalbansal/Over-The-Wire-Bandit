# over-the-wire-bandit
Over The Wire Bandit

To make Connection:
Command - ssh bandit0@bandit.labs.overthewire.org -p 2220

ls - To list all visible files in a directory
more _fileName_ - To display content of a _fileName_
Level 0 - NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

more "_fileName_" - To display content of _fileName_ (used when _fileName_ has spaces or unique symbols)
more ./- -  To display content of file with name "-"
Level 1 - rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

cd _directoryName_ - To enter a directory
Level 2 - aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

https://www.rapidtables.com/code/linux/ls.html
ls -a - To display all files including hidden files (hidden files are files whose name starts with .)
Level 3 - 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

more ./-file00 - To display content of file of name "-file00"
file ./* - To know file type of all files
Level 4 - lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

find .-size 1033c - To display files with size of 1033c or 1033 bytes
Level 5 - P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

find / -user bandit7 -group bandit6 -size 33c - All the files satisfy the following criterias
cat /var/lib/dpkg/info/bandit7.password
Level 6 - z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

cat data.txt | grep millionth - To show lines with the word millionth in it
Level 7 - TESKZC0XvTetK0S9xNwm25STk5iWrBvP

cat data.txt | sort | uniq -u -  To show lines that occurs only once
Level 8 - EN632PlfYiZbn3PhVK3XOGSlNInNE00t

strings data.txt | grep = - To show lines that are human readable strings and contain "="
Level 9 - G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

cat data.txt | base64 --decode - To show lines that are base64 encoded in decoded form
Level 10 - 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

cat data.txt | tr a-zA-Z n-za-mN-ZA-M
Level 11 - JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

cat data.txt
mkdir /tmp/pavan
cp data.txt /tmp/pavan
cd /tmp/pavan
ls
file data.txt
xxd -r data.txt data1
file data1
mv data1 data2.gz
gzip -d data2.gz
file data2
mv data2 data3.bz2
bzip2 -d data3.bz2
file data3
mv data3 data4.gz
gzip -d data4.gz
file data4
tar -xvf data4
file data5.bin
tar -xvf data5.bin
file data6.bin
mv data6.bin data7.bz2
bzip2 -d data7.bz2
file data7
tar -xvf data7
file data8.bin
mv data8.bin data9.gz
gzip -d data9.gz
file data9
cat data9
Level 12 - wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

ssh bandit14@localhost -i sshkey.private
Level 13 - N/A
