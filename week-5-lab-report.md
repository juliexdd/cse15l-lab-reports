#### Week 5 Lab Report - Julie Nguyen
# Lab Report 3 - Researching Commands

## Researching Commands - `find` Command

## Finding 4 Interesting Command-Line Options/Alternative Ways To Use `find`
---
1. `find -type`
- `-type` refers to finding a specific type of file rather than simply listing out all of the files within the directory.
- There are multiple options to using the `-type` command like `find -type f` to find all files, and `find -type d` to list out directories instead.
- This is useful because it helps sort files by their type(s)!

- `find -type` Command Input - Example 1
```
$ find -type f
```
- Output
```
./non-fiction/OUP/Abernathy/ch1.txt
./non-fiction/OUP/Abernathy/ch14.txt
./non-fiction/OUP/Abernathy/ch15.txt
./non-fiction/OUP/Abernathy/ch2.txt
./non-fiction/OUP/Abernathy/ch3.txt
./non-fiction/OUP/Abernathy/ch6.txt
./non-fiction/OUP/Abernathy/ch7.txt
./non-fiction/OUP/Abernathy/ch8.txt
./non-fiction/OUP/Abernathy/ch9.txt
./non-fiction/OUP/Berk/CH4.txt
./non-fiction/OUP/Berk/ch1.txt
./non-fiction/OUP/Berk/ch2.txt
./non-fiction/OUP/Berk/ch7.txt
./non-fiction/OUP/Castro/chA.txt
./non-fiction/OUP/Castro/chB.txt
./non-fiction/OUP/Castro/chC.txt
./non-fiction/OUP/Castro/chL.txt
./non-fiction/OUP/Castro/chM.txt
./non-fiction/OUP/Castro/chN.txt
./non-fiction/OUP/Castro/chO.txt
./non-fiction/OUP/Castro/chP.txt
./non-fiction/OUP/Castro/chQ.txt
./non-fiction/OUP/Castro/chR.txt
./non-fiction/OUP/Castro/chV.txt
./non-fiction/OUP/Castro/chW.txt
./non-fiction/OUP/Castro/chY.txt
./non-fiction/OUP/Castro/chZ.txt
./non-fiction/OUP/Fletcher/ch1.txt
./non-fiction/OUP/Fletcher/ch10.txt
./non-fiction/OUP/Fletcher/ch2.txt
./non-fiction/OUP/Fletcher/ch5.txt
./non-fiction/OUP/Fletcher/ch6.txt
./non-fiction/OUP/Fletcher/ch9.txt
./non-fiction/OUP/Kauffman/ch1.txt
./non-fiction/OUP/Kauffman/ch10.txt
./non-fiction/OUP/Kauffman/ch3.txt
./non-fiction/OUP/Kauffman/ch4.txt
./non-fiction/OUP/Kauffman/ch5.txt
./non-fiction/OUP/Kauffman/ch6.txt
./non-fiction/OUP/Kauffman/ch7.txt
./non-fiction/OUP/Kauffman/ch8.txt
./non-fiction/OUP/Kauffman/ch9.txt
./non-fiction/OUP/Rybczynski/ch1.txt
./non-fiction/OUP/Rybczynski/ch2.txt
./non-fiction/OUP/Rybczynski/ch3.txt
./travel_guides/berlitz1/HandRHawaii.txt
./travel_guides/berlitz1/HandRHongKong.txt
./travel_guides/berlitz1/HandRIbiza.txt
./travel_guides/berlitz1/HandRIsrael.txt
./travel_guides/berlitz1/HandRIstanbul.txt
./travel_guides/berlitz1/HandRJamaica.txt
./travel_guides/berlitz1/HandRJerusalem.txt
./travel_guides/berlitz1/HandRLakeDistrict.txt
./travel_guides/berlitz1/HandRLasVegas.txt
./travel_guides/berlitz1/HandRLisbon.txt
./travel_guides/berlitz1/HandRLosAngeles.txt
./travel_guides/berlitz1/HandRMadeira.txt
./travel_guides/berlitz1/HandRMadrid.txt
./travel_guides/berlitz1/HandRMallorca.txt
./travel_guides/berlitz1/HistoryDublin.txt
./travel_guides/berlitz1/HistoryEdinburgh.txt
./travel_guides/berlitz1/HistoryEgypt.txt
./travel_guides/berlitz1/HistoryFWI.txt
./travel_guides/berlitz1/HistoryFrance.txt
./travel_guides/berlitz1/HistoryGreek.txt
./travel_guides/berlitz1/HistoryHawaii.txt
./travel_guides/berlitz1/HistoryHongKong.txt
./travel_guides/berlitz1/HistoryIbiza.txt
./travel_guides/berlitz1/HistoryIndia.txt
./travel_guides/berlitz1/HistoryIsrael.txt
./travel_guides/berlitz1/HistoryIstanbul.txt
./travel_guides/berlitz1/HistoryItaly.txt
./travel_guides/berlitz1/HistoryJamaica.txt
./travel_guides/berlitz1/HistoryJapan.txt
./travel_guides/berlitz1/HistoryJerusalem.txt
./travel_guides/berlitz1/HistoryLakeDistrict.txt
./travel_guides/berlitz1/HistoryLasVegas.txt
./travel_guides/berlitz1/HistoryMadeira.txt
./travel_guides/berlitz1/HistoryMadrid.txt
./travel_guides/berlitz1/HistoryMalaysia.txt
./travel_guides/berlitz1/HistoryMallorca.txt
./travel_guides/berlitz1/IntroDublin.txt
./travel_guides/berlitz1/IntroEdinburgh.txt
./travel_guides/berlitz1/IntroEgypt.txt
./travel_guides/berlitz1/IntroFWI.txt
./travel_guides/berlitz1/IntroFrance.txt
./travel_guides/berlitz1/IntroGreek.txt
./travel_guides/berlitz1/IntroHongKong.txt
./travel_guides/berlitz1/IntroIbiza.txt
./travel_guides/berlitz1/IntroIndia.txt
./travel_guides/berlitz1/IntroIsrael.txt
./travel_guides/berlitz1/IntroIstanbul.txt
./travel_guides/berlitz1/IntroItaly.txt
./travel_guides/berlitz1/IntroJamaica.txt
./travel_guides/berlitz1/IntroJapan.txt
./travel_guides/berlitz1/IntroJerusalem.txt
./travel_guides/berlitz1/IntroLakeDistrict.txt
./travel_guides/berlitz1/IntroLasVegas.txt
./travel_guides/berlitz1/IntroLosAngeles.txt
./travel_guides/berlitz1/IntroMadeira.txt
./travel_guides/berlitz1/IntroMadrid.txt
./travel_guides/berlitz1/IntroMalaysia.txt
./travel_guides/berlitz1/IntroMallorca.txt
./travel_guides/berlitz1/JungleMalaysia.txt
./travel_guides/berlitz1/WhatToDublin.txt
./travel_guides/berlitz1/WhatToEdinburgh.txt
./travel_guides/berlitz1/WhatToEgypt.txt
./travel_guides/berlitz1/WhatToFWI.txt
./travel_guides/berlitz1/WhatToFrance.txt
./travel_guides/berlitz1/WhatToGreek.txt
./travel_guides/berlitz1/WhatToHawaii.txt
./travel_guides/berlitz1/WhatToHongKong.txt
./travel_guides/berlitz1/WhatToIbiza.txt
./travel_guides/berlitz1/WhatToIndia.txt
./travel_guides/berlitz1/WhatToIsrael.txt
./travel_guides/berlitz1/WhatToIstanbul.txt
./travel_guides/berlitz1/WhatToItaly.txt
./travel_guides/berlitz1/WhatToJamaica.txt
./travel_guides/berlitz1/WhatToJapan.txt
./travel_guides/berlitz1/WhatToLakeDistrict.txt
./travel_guides/berlitz1/WhatToLasVegas.txt
./travel_guides/berlitz1/WhatToLosAngeles.txt
./travel_guides/berlitz1/WhatToMadeira.txt
./travel_guides/berlitz1/WhatToMalaysia.txt
./travel_guides/berlitz1/WhatToMallorca.txt
./travel_guides/berlitz1/WhereToDublin.txt
./travel_guides/berlitz1/WhereToEdinburgh.txt
./travel_guides/berlitz1/WhereToEgypt.txt
./travel_guides/berlitz1/WhereToFWI.txt
./travel_guides/berlitz1/WhereToFrance.txt
./travel_guides/berlitz1/WhereToGreek.txt
./travel_guides/berlitz1/WhereToHawaii.txt
./travel_guides/berlitz1/WhereToHongKong.txt
./travel_guides/berlitz1/WhereToIbiza.txt
./travel_guides/berlitz1/WhereToIndia.txt
./travel_guides/berlitz1/WhereToIsrael.txt
./travel_guides/berlitz1/WhereToIstanbul.txt
./travel_guides/berlitz1/WhereToItaly.txt
./travel_guides/berlitz1/WhereToJapan.txt
./travel_guides/berlitz1/WhereToJerusalem.txt
./travel_guides/berlitz1/WhereToLakeDistrict.txt
./travel_guides/berlitz1/WhereToLosAngeles.txt
./travel_guides/berlitz1/WhereToMadeira.txt
./travel_guides/berlitz1/WhereToMadrid.txt
./travel_guides/berlitz1/WhereToMalaysia.txt
./travel_guides/berlitz1/WhereToMallorca.txt
./travel_guides/berlitz2/Algarve-History.txt
./travel_guides/berlitz2/Algarve-Intro.txt
./travel_guides/berlitz2/Algarve-WhatToDo.txt
./travel_guides/berlitz2/Algarve-WhereToGo.txt
./travel_guides/berlitz2/Amsterdam-History.txt
./travel_guides/berlitz2/Amsterdam-Intro.txt
./travel_guides/berlitz2/Amsterdam-WhatToDo.txt
./travel_guides/berlitz2/Amsterdam-WhereToGo.txt
./travel_guides/berlitz2/Athens-History.txt
./travel_guides/berlitz2/Athens-Intro.txt
./travel_guides/berlitz2/Athens-WhatToDo.txt
./travel_guides/berlitz2/Athens-WhereToGo.txt
./travel_guides/berlitz2/Bahamas-History.txt
./travel_guides/berlitz2/Bahamas-Intro.txt
./travel_guides/berlitz2/Bahamas-WhatToDo.txt
./travel_guides/berlitz2/Bahamas-WhereToGo.txt
./travel_guides/berlitz2/Bali-History.txt
./travel_guides/berlitz2/Bali-WhatToDo.txt
./travel_guides/berlitz2/Bali-WhereToGo.txt
./travel_guides/berlitz2/Barcelona-History.txt
./travel_guides/berlitz2/Barcelona-WhatToDo.txt
./travel_guides/berlitz2/Barcelona-WhereToGo.txt
./travel_guides/berlitz2/Beijing-History.txt
./travel_guides/berlitz2/Beijing-WhatToDo.txt
./travel_guides/berlitz2/Beijing-WhereToGo.txt
./travel_guides/berlitz2/Berlin-History.txt
./travel_guides/berlitz2/Berlin-WhatToDo.txt
./travel_guides/berlitz2/Berlin-WhereToGo.txt
./travel_guides/berlitz2/Bermuda-WhatToDo.txt
./travel_guides/berlitz2/Bermuda-WhereToGo.txt
./travel_guides/berlitz2/Bermuda-history.txt
./travel_guides/berlitz2/Boston-WhereToGo.txt
./travel_guides/berlitz2/Budapest-History.txt
./travel_guides/berlitz2/Budapest-WhatToDo.txt
./travel_guides/berlitz2/Budapest-WhereoGo.txt
./travel_guides/berlitz2/California-History.txt
./travel_guides/berlitz2/California-WhatToDo.txt
./travel_guides/berlitz2/California-WhereToGo.txt
./travel_guides/berlitz2/Canada-History.txt
./travel_guides/berlitz2/Canada-WhereToGo.txt
./travel_guides/berlitz2/CanaryIslands-History.txt
./travel_guides/berlitz2/CanaryIslands-WhatToDo.txt
./travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
./travel_guides/berlitz2/Cancun-History.txt
./travel_guides/berlitz2/Cancun-WhatToDo.txt
./travel_guides/berlitz2/Cancun-WhereToGo.txt
./travel_guides/berlitz2/China-History.txt
./travel_guides/berlitz2/China-WhatToDo.txt
./travel_guides/berlitz2/China-WhereToGo.txt
./travel_guides/berlitz2/Costa-History.txt
./travel_guides/berlitz2/Costa-WhatToDo.txt
./travel_guides/berlitz2/Costa-WhereToGo.txt
./travel_guides/berlitz2/CostaBlanca-History.txt
./travel_guides/berlitz2/CostaBlanca-WhatToDo.txt
./travel_guides/berlitz2/Crete-History.txt
./travel_guides/berlitz2/Crete-WhatToDo.txt
./travel_guides/berlitz2/Crete-WhereToGo.txt
./travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
./travel_guides/berlitz2/Cuba-History.txt
./travel_guides/berlitz2/Cuba-WhatToDo.txt
./travel_guides/berlitz2/Cuba-WhereToGo.txt
./travel_guides/berlitz2/Nepal-History.txt
./travel_guides/berlitz2/Nepal-WhatToDo.txt
./travel_guides/berlitz2/Nepal-WhereToGo.txt
./travel_guides/berlitz2/NewOrleans-History.txt
./travel_guides/berlitz2/Paris-WhatToDo.txt
./travel_guides/berlitz2/Paris-WhereToGo.txt
./travel_guides/berlitz2/Poland-History.txt
./travel_guides/berlitz2/Poland-WhatToDo.txt
./travel_guides/berlitz2/Portugal-History.txt
./travel_guides/berlitz2/Portugal-WhatToDo.txt
./travel_guides/berlitz2/Portugal-WhereToGo.txt
./travel_guides/berlitz2/PuertoRico-History.txt
./travel_guides/berlitz2/PuertoRico-WhatToDo.txt
./travel_guides/berlitz2/PuertoRico-WhereToGo.txt
./travel_guides/berlitz2/Vallarta-History.txt
./travel_guides/berlitz2/Vallarta-WhatToDo.txt
./travel_guides/berlitz2/Vallarta-WhereToGo.txt
```
- Here, the output displays all files in `./written_2`, and it does not display directories like `./travel_guides/berlitz2` or `./non-fiction/OUP/Kauffman`

- `find -type` Command Input - Example 2
```
$ find -type d
```
- Output
```
.
./non-fiction
./non-fiction/OUP
./non-fiction/OUP/Abernathy
./non-fiction/OUP/Berk
./non-fiction/OUP/Castro
./non-fiction/OUP/Fletcher
./non-fiction/OUP/Kauffman
./non-fiction/OUP/Rybczynski
./travel_guides
./travel_guides/berlitz1
./travel_guides/berlitz2
```
- Here, the output displays all directories in `./written_2`, and it does not display any `.txt` files within these directories.
---
2. `find -size`
- `-size` refers to finding files that falls under or over certain sizes like `c` for bytes, `k` kilobytes, `M` for megabytes, `G` for gigabytes, etc.
- Adding a `+` or `-` sign in front of the letter determines if it finds files greater than or less than the specified size.
- This is useful because it helps find files' sizes if they fall under or over a size limit!

- `find -size` Command Input - Example 1
```
$ find -size +80k
```
- Output
```
./non-fiction/OUP/Berk/CH4.txt
./non-fiction/OUP/Berk/ch1.txt
./non-fiction/OUP/Berk/ch2.txt
./non-fiction/OUP/Kauffman/ch8.txt
./non-fiction/OUP/Kauffman/ch9.txt
./travel_guides/berlitz1/WhatToJamaica.txt
./travel_guides/berlitz1/WhereToDublin.txt
./travel_guides/berlitz1/WhereToEgypt.txt
./travel_guides/berlitz1/WhereToFrance.txt
./travel_guides/berlitz1/WhereToIndia.txt
./travel_guides/berlitz1/WhereToIsrael.txt
./travel_guides/berlitz1/WhereToIstanbul.txt
./travel_guides/berlitz1/WhereToItaly.txt
./travel_guides/berlitz1/WhereToJapan.txt
./travel_guides/berlitz1/WhereToLakeDistrict.txt
./travel_guides/berlitz1/WhereToMalaysia.txt
./travel_guides/berlitz2/Canada-WhereToGo.txt
./travel_guides/berlitz2/China-WhereToGo.txt
./travel_guides/berlitz2/Portugal-WhereToGo.txt
```
- Here, the output displays all files in `./written_2` that are greater than 80 kilobytes.

- `find -size` Command Input - Example 2
```
$ find -size -1000c
```
- Output
```
./travel_guides/berlitz1/HandRIbiza.txt
./travel_guides/berlitz1/HandRIstanbul.txt
```
- Here, the output displays all files in `./written_2` than are less than 1000 bytes.
---
3. `find -mtime`
- `-mtime` refers to finding files that falls under or over a specific amount of days since its modified time like `-mtime -7` finds files modified less than 7 days ago. `-mtime +9` finds files modified over 9 days ago.
- Adding a `+` or `-` sign in front of the `-mtime` determines if it finds files greates than or less than the specified amount of days.
- Adding a `-ls` after the command will show the time and date modified as well!
- This is useful because it helps find files modified after or before a certain time period!

- `find -mtime` Command Input - Example 1
```
$ find -mtime -7 -ls
```
- Output
```
60376499    4 drwxr-s---   4 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 .
60376514    4 drwxr-s---   3 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction
60376515    4 drwxr-s---   8 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP
60376516    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Abernathy
60376517   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    46915 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch1.txt
60376518   44 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    39905 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch14.txt
60376519   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    43918 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch15.txt
60376520   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    44782 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch2.txt
60376521   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    35141 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch3.txt
60376522   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    42225 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch6.txt
60376523   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    42444 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch7.txt
60376524   56 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    52468 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch8.txt
60376525   36 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    31283 Feb  7 21:16 ./non-fiction/OUP/Abernathy/ch9.txt
60376526    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Berk
60376527  108 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   103491 Feb  7 21:16 ./non-fiction/OUP/Berk/CH4.txt
60376528   96 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    92355 Feb  7 21:16 ./non-fiction/OUP/Berk/ch1.txt
60376529  108 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   102942 Feb  7 21:16 ./non-fiction/OUP/Berk/ch2.txt
60376530   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    66887 Feb  7 21:16 ./non-fiction/OUP/Berk/ch7.txt
60376531    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Castro
60376532   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    35675 Feb  7 21:16 ./non-fiction/OUP/Castro/chA.txt
60376533   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    32819 Feb  7 21:16 ./non-fiction/OUP/Castro/chB.txt
60376534   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    23635 Feb  7 21:16 ./non-fiction/OUP/Castro/chC.txt
60376535   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    24476 Feb  7 21:16 ./non-fiction/OUP/Castro/chL.txt
60376536   60 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    55410 Feb  7 21:16 ./non-fiction/OUP/Castro/chM.txt
60376537   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     9182 Feb  7 21:16 ./non-fiction/OUP/Castro/chN.txt
60376538   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8349 Feb  7 21:16 ./non-fiction/OUP/Castro/chO.txt
60376539   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    41470 Feb  7 21:16 ./non-fiction/OUP/Castro/chP.txt
60376540   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8274 Feb  7 21:16 ./non-fiction/OUP/Castro/chQ.txt
60376541   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    33420 Feb  7 21:16 ./non-fiction/OUP/Castro/chR.txt
60376542   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19909 Feb  7 21:16 ./non-fiction/OUP/Castro/chV.txt
60376543    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     6724 Feb  7 21:16 ./non-fiction/OUP/Castro/chW.txt
60376544    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     5424 Feb  7 21:16 ./non-fiction/OUP/Castro/chY.txt
60376545    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     5431 Feb  7 21:16 ./non-fiction/OUP/Castro/chZ.txt
60376546    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Fletcher
60376547   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    46376 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch1.txt
60376548   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    33013 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch10.txt
60376549   56 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    51325 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch2.txt
60376550   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    48389 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch5.txt
60376551   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    68106 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch6.txt
60376552   60 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    53257 Feb  7 21:16 ./non-fiction/OUP/Fletcher/ch9.txt
60376553    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Kauffman
60376554   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    65578 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch1.txt
60376555   68 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    64908 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch10.txt
60376556   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    80544 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch3.txt
60376557   80 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    74448 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch4.txt
60376558   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    27196 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch5.txt
60376559   68 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    61513 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch6.txt
60376560   56 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    50095 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch7.txt
60376561  104 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    99145 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch8.txt
60376562   92 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    86220 Feb  7 21:16 ./non-fiction/OUP/Kauffman/ch9.txt
60376563    4 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./non-fiction/OUP/Rybczynski
60376564   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    34412 Feb  7 21:16 ./non-fiction/OUP/Rybczynski/ch1.txt
60376565   44 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    38052 Feb  7 21:16 ./non-fiction/OUP/Rybczynski/ch2.txt
60376566   56 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    52179 Feb  7 21:16 ./non-fiction/OUP/Rybczynski/ch3.txt
60376567    4 drwxr-s---   4 cs15lwi23aqg ieng6_cs15lwi23     4096 Feb  7 21:16 ./travel_guides
60376568    8 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     8192 Feb  7 21:16 ./travel_guides/berlitz1
60376569   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16271 Feb  7 21:16 ./travel_guides/berlitz1/HandRHawaii.txt
60376570    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1193 Feb  7 21:16 ./travel_guides/berlitz1/HandRHongKong.txt
60376571    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23      675 Feb  7 21:16 ./travel_guides/berlitz1/HandRIbiza.txt
60376572   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    25689 Feb  7 21:16 ./travel_guides/berlitz1/HandRIsrael.txt
60376573    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23      931 Feb  7 21:16 ./travel_guides/berlitz1/HandRIstanbul.txt
60376574   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    25434 Feb  7 21:16 ./travel_guides/berlitz1/HandRJamaica.txt
60376575    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1446 Feb  7 21:16 ./travel_guides/berlitz1/HandRJerusalem.txt
60376576    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1528 Feb  7 21:16 ./travel_guides/berlitz1/HandRLakeDistrict.txt
60376577    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1547 Feb  7 21:16 ./travel_guides/berlitz1/HandRLasVegas.txt
60376578    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1067 Feb  7 21:16 ./travel_guides/berlitz1/HandRLisbon.txt
60376579    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1254 Feb  7 21:16 ./travel_guides/berlitz1/HandRLosAngeles.txt
60376580    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1433 Feb  7 21:16 ./travel_guides/berlitz1/HandRMadeira.txt
60376581   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14092 Feb  7 21:16 ./travel_guides/berlitz1/HandRMadrid.txt
60376582    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     1445 Feb  7 21:16 ./travel_guides/berlitz1/HandRMallorca.txt
60376583   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15962 Feb  7 21:16 ./travel_guides/berlitz1/HistoryDublin.txt
60376584   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21027 Feb  7 21:16 ./travel_guides/berlitz1/HistoryEdinburgh.txt
60376585   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18298 Feb  7 21:16 ./travel_guides/berlitz1/HistoryEgypt.txt
60376586   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15011 Feb  7 21:16 ./travel_guides/berlitz1/HistoryFWI.txt
60376587   44 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    38509 Feb  7 21:16 ./travel_guides/berlitz1/HistoryFrance.txt
60376588   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18666 Feb  7 21:16 ./travel_guides/berlitz1/HistoryGreek.txt
60376589   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16522 Feb  7 21:16 ./travel_guides/berlitz1/HistoryHawaii.txt
60376590   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14614 Feb  7 21:16 ./travel_guides/berlitz1/HistoryHongKong.txt
60376591   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12703 Feb  7 21:16 ./travel_guides/berlitz1/HistoryIbiza.txt
60376592   60 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    54898 Feb  7 21:16 ./travel_guides/berlitz1/HistoryIndia.txt
60376593   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16573 Feb  7 21:16 ./travel_guides/berlitz1/HistoryIsrael.txt
60376594   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    27099 Feb  7 21:16 ./travel_guides/berlitz1/HistoryIstanbul.txt
60376595   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    48191 Feb  7 21:16 ./travel_guides/berlitz1/HistoryItaly.txt
60376596   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    17168 Feb  7 21:16 ./travel_guides/berlitz1/HistoryJamaica.txt
60376597   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    41789 Feb  7 21:16 ./travel_guides/berlitz1/HistoryJapan.txt
60376598   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18491 Feb  7 21:16 ./travel_guides/berlitz1/HistoryJerusalem.txt
60376599   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13596 Feb  7 21:16 ./travel_guides/berlitz1/HistoryLakeDistrict.txt
60376600   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18968 Feb  7 21:16 ./travel_guides/berlitz1/HistoryLasVegas.txt
60376601   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11857 Feb  7 21:16 ./travel_guides/berlitz1/HistoryMadeira.txt
60376602   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12519 Feb  7 21:16 ./travel_guides/berlitz1/HistoryMadrid.txt
60376603   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    35725 Feb  7 21:16 ./travel_guides/berlitz1/HistoryMalaysia.txt
60376604   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13730 Feb  7 21:16 ./travel_guides/berlitz1/HistoryMallorca.txt
60376605    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     7820 Feb  7 21:16 ./travel_guides/berlitz1/IntroDublin.txt
60376606   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     9427 Feb  7 21:16 ./travel_guides/berlitz1/IntroEdinburgh.txt
60376607    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     7989 Feb  7 21:16 ./travel_guides/berlitz1/IntroEgypt.txt
60376608    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     7684 Feb  7 21:16 ./travel_guides/berlitz1/IntroFWI.txt
60376609   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11010 Feb  7 21:16 ./travel_guides/berlitz1/IntroFrance.txt
60376610   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8323 Feb  7 21:16 ./travel_guides/berlitz1/IntroGreek.txt
60376611    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     5784 Feb  7 21:16 ./travel_guides/berlitz1/IntroHongKong.txt
60376612    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     6210 Feb  7 21:16 ./travel_guides/berlitz1/IntroIbiza.txt
60376613   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    26436 Feb  7 21:16 ./travel_guides/berlitz1/IntroIndia.txt
60376614    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     5318 Feb  7 21:16 ./travel_guides/berlitz1/IntroIsrael.txt
60376615    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     7212 Feb  7 21:16 ./travel_guides/berlitz1/IntroIstanbul.txt
60376616   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12345 Feb  7 21:16 ./travel_guides/berlitz1/IntroItaly.txt
60376617   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    10468 Feb  7 21:16 ./travel_guides/berlitz1/IntroJamaica.txt
60376618   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19138 Feb  7 21:16 ./travel_guides/berlitz1/IntroJapan.txt
60376619   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    10132 Feb  7 21:16 ./travel_guides/berlitz1/IntroJerusalem.txt
60376620   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11857 Feb  7 21:16 ./travel_guides/berlitz1/IntroLakeDistrict.txt
60376621   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11886 Feb  7 21:16 ./travel_guides/berlitz1/IntroLasVegas.txt
60376622    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     6323 Feb  7 21:16 ./travel_guides/berlitz1/IntroLosAngeles.txt
60376623   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     9927 Feb  7 21:16 ./travel_guides/berlitz1/IntroMadeira.txt
60376624   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11562 Feb  7 21:16 ./travel_guides/berlitz1/IntroMadrid.txt
60376625   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8528 Feb  7 21:16 ./travel_guides/berlitz1/IntroMalaysia.txt
60376626   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     9291 Feb  7 21:16 ./travel_guides/berlitz1/IntroMallorca.txt
60376627    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     6818 Feb  7 21:16 ./travel_guides/berlitz1/JungleMalaysia.txt
60376628   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    20985 Feb  7 21:16 ./travel_guides/berlitz1/WhatToDublin.txt
60376629   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21152 Feb  7 21:16 ./travel_guides/berlitz1/WhatToEdinburgh.txt
60376630   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21659 Feb  7 21:16 ./travel_guides/berlitz1/WhatToEgypt.txt
60376631   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    26623 Feb  7 21:16 ./travel_guides/berlitz1/WhatToFWI.txt
60376632    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     2324 Feb  7 21:16 ./travel_guides/berlitz1/WhatToFrance.txt
60376633   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18503 Feb  7 21:16 ./travel_guides/berlitz1/WhatToGreek.txt
60376634    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     2477 Feb  7 21:16 ./travel_guides/berlitz1/WhatToHawaii.txt
60376635   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    24756 Feb  7 21:16 ./travel_guides/berlitz1/WhatToHongKong.txt
60376636   44 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    38183 Feb  7 21:16 ./travel_guides/berlitz1/WhatToIbiza.txt
60376637   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18898 Feb  7 21:16 ./travel_guides/berlitz1/WhatToIndia.txt
60376638   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21343 Feb  7 21:16 ./travel_guides/berlitz1/WhatToIsrael.txt
60376639   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    26999 Feb  7 21:16 ./travel_guides/berlitz1/WhatToIstanbul.txt
60376640   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    22430 Feb  7 21:16 ./travel_guides/berlitz1/WhatToItaly.txt
60376641   92 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    86290 Feb  7 21:16 ./travel_guides/berlitz1/WhatToJamaica.txt
60376642   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    35438 Feb  7 21:16 ./travel_guides/berlitz1/WhatToJapan.txt
60376643   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21180 Feb  7 21:16 ./travel_guides/berlitz1/WhatToLakeDistrict.txt
60376644   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    48170 Feb  7 21:16 ./travel_guides/berlitz1/WhatToLasVegas.txt
60376645   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    24076 Feb  7 21:16 ./travel_guides/berlitz1/WhatToLosAngeles.txt
60376646   32 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    28497 Feb  7 21:16 ./travel_guides/berlitz1/WhatToMadeira.txt
60376647   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    23497 Feb  7 21:16 ./travel_guides/berlitz1/WhatToMalaysia.txt
60376648   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    17417 Feb  7 21:16 ./travel_guides/berlitz1/WhatToMallorca.txt
60376649   92 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    87384 Feb  7 21:16 ./travel_guides/berlitz1/WhereToDublin.txt
60376650   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    79007 Feb  7 21:16 ./travel_guides/berlitz1/WhereToEdinburgh.txt
60376651   88 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    85505 Feb  7 21:16 ./travel_guides/berlitz1/WhereToEgypt.txt
60376652   68 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    64916 Feb  7 21:16 ./travel_guides/berlitz1/WhereToFWI.txt
60376653  256 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   253959 Feb  7 21:16 ./travel_guides/berlitz1/WhereToFrance.txt
60376654   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    80111 Feb  7 21:16 ./travel_guides/berlitz1/WhereToGreek.txt
60376655    4 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     2309 Feb  7 21:16 ./travel_guides/berlitz1/WhereToHawaii.txt
60376656   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    67601 Feb  7 21:16 ./travel_guides/berlitz1/WhereToHongKong.txt
60376657   48 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    42155 Feb  7 21:16 ./travel_guides/berlitz1/WhereToIbiza.txt
60376658  176 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   172986 Feb  7 21:16 ./travel_guides/berlitz1/WhereToIndia.txt
60376660   88 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    84424 Feb  7 21:16 ./travel_guides/berlitz1/WhereToIsrael.txt
60374912   92 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    88932 Feb  7 21:16 ./travel_guides/berlitz1/WhereToIstanbul.txt
60376661  292 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   294602 Feb  7 21:16 ./travel_guides/berlitz1/WhereToItaly.txt
60376662  192 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   189061 Feb  7 21:16 ./travel_guides/berlitz1/WhereToJapan.txt
60376663   80 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    76530 Feb  7 21:16 ./travel_guides/berlitz1/WhereToJerusalem.txt
60376664   88 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    84671 Feb  7 21:16 ./travel_guides/berlitz1/WhereToLakeDistrict.txt
60376665   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    77840 Feb  7 21:16 ./travel_guides/berlitz1/WhereToLosAngeles.txt
60376666   68 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    65176 Feb  7 21:16 ./travel_guides/berlitz1/WhereToMadeira.txt
60376667   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    78028 Feb  7 21:16 ./travel_guides/berlitz1/WhereToMadrid.txt
60376668  184 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   180940 Feb  7 21:16 ./travel_guides/berlitz1/WhereToMalaysia.txt
60376669   80 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    74270 Feb  7 21:16 ./travel_guides/berlitz1/WhereToMallorca.txt
60376670    8 drwxr-s---   2 cs15lwi23aqg ieng6_cs15lwi23     8192 Feb  7 21:16 ./travel_guides/berlitz2
60376671   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15389 Feb  7 21:16 ./travel_guides/berlitz2/Algarve-History.txt
60376672    8 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     7996 Feb  7 21:16 ./travel_guides/berlitz2/Algarve-Intro.txt
60376673   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16133 Feb  7 21:16 ./travel_guides/berlitz2/Algarve-WhatToDo.txt
60376674   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    69415 Feb  7 21:16 ./travel_guides/berlitz2/Algarve-WhereToGo.txt
60376675   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15758 Feb  7 21:16 ./travel_guides/berlitz2/Amsterdam-History.txt
60376676   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8765 Feb  7 21:16 ./travel_guides/berlitz2/Amsterdam-Intro.txt
60376677   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16133 Feb  7 21:16 ./travel_guides/berlitz2/Amsterdam-WhatToDo.txt
60376678   64 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    58911 Feb  7 21:16 ./travel_guides/berlitz2/Amsterdam-WhereToGo.txt
60376679   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    20481 Feb  7 21:16 ./travel_guides/berlitz2/Athens-History.txt
60376680   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     8907 Feb  7 21:16 ./travel_guides/berlitz2/Athens-Intro.txt
60376681   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    17143 Feb  7 21:16 ./travel_guides/berlitz2/Athens-WhatToDo.txt
60376682   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    71349 Feb  7 21:16 ./travel_guides/berlitz2/Athens-WhereToGo.txt
60376683   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16802 Feb  7 21:16 ./travel_guides/berlitz2/Bahamas-History.txt
60376684   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23     9107 Feb  7 21:16 ./travel_guides/berlitz2/Bahamas-Intro.txt
60376685   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19719 Feb  7 21:16 ./travel_guides/berlitz2/Bahamas-WhatToDo.txt
60376686   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73435 Feb  7 21:16 ./travel_guides/berlitz2/Bahamas-WhereToGo.txt
60376687   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16431 Feb  7 21:16 ./travel_guides/berlitz2/Bali-History.txt
60376688   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18112 Feb  7 21:16 ./travel_guides/berlitz2/Bali-WhatToDo.txt
60376689   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    78053 Feb  7 21:16 ./travel_guides/berlitz2/Bali-WhereToGo.txt
60376690   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13127 Feb  7 21:16 ./travel_guides/berlitz2/Barcelona-History.txt
60376691   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19052 Feb  7 21:16 ./travel_guides/berlitz2/Barcelona-WhatToDo.txt
60376692   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    72769 Feb  7 21:16 ./travel_guides/berlitz2/Barcelona-WhereToGo.txt
60376693   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12702 Feb  7 21:16 ./travel_guides/berlitz2/Beijing-History.txt
60376694   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    21838 Feb  7 21:16 ./travel_guides/berlitz2/Beijing-WhatToDo.txt
60376695   68 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    63667 Feb  7 21:16 ./travel_guides/berlitz2/Beijing-WhereToGo.txt
60376696   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    22126 Feb  7 21:16 ./travel_guides/berlitz2/Berlin-History.txt
60376697   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14688 Feb  7 21:16 ./travel_guides/berlitz2/Berlin-WhatToDo.txt
60376698   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    69890 Feb  7 21:16 ./travel_guides/berlitz2/Berlin-WhereToGo.txt
60376699   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    22386 Feb  7 21:16 ./travel_guides/berlitz2/Bermuda-WhatToDo.txt
60376700   64 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    60475 Feb  7 21:16 ./travel_guides/berlitz2/Bermuda-WhereToGo.txt
60376701   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15046 Feb  7 21:16 ./travel_guides/berlitz2/Bermuda-history.txt
60376702   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73074 Feb  7 21:16 ./travel_guides/berlitz2/Boston-WhereToGo.txt
60376703   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12872 Feb  7 21:16 ./travel_guides/berlitz2/Budapest-History.txt
60376704   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16916 Feb  7 21:16 ./travel_guides/berlitz2/Budapest-WhatToDo.txt
60376705   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73535 Feb  7 21:16 ./travel_guides/berlitz2/Budapest-WhereoGo.txt
60376706   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19139 Feb  7 21:16 ./travel_guides/berlitz2/California-History.txt
60376707   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16255 Feb  7 21:16 ./travel_guides/berlitz2/California-WhatToDo.txt
60376708   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73702 Feb  7 21:16 ./travel_guides/berlitz2/California-WhereToGo.txt
60376709   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    46093 Feb  7 21:16 ./travel_guides/berlitz2/Canada-History.txt
60376710  236 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   235947 Feb  7 21:16 ./travel_guides/berlitz2/Canada-WhereToGo.txt
60376711   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13919 Feb  7 21:16 ./travel_guides/berlitz2/CanaryIslands-History.txt
60376712   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15587 Feb  7 21:16 ./travel_guides/berlitz2/CanaryIslands-WhatToDo.txt
60376713   80 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    76744 Feb  7 21:16 ./travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
60376714   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15364 Feb  7 21:16 ./travel_guides/berlitz2/Cancun-History.txt
60376715   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18673 Feb  7 21:16 ./travel_guides/berlitz2/Cancun-WhatToDo.txt
60376716   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    66453 Feb  7 21:16 ./travel_guides/berlitz2/Cancun-WhereToGo.txt
60376717   36 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    29333 Feb  7 21:16 ./travel_guides/berlitz2/China-History.txt
60376718   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    12906 Feb  7 21:16 ./travel_guides/berlitz2/China-WhatToDo.txt
60376719  200 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   198080 Feb  7 21:16 ./travel_guides/berlitz2/China-WhereToGo.txt
60376720   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16143 Feb  7 21:16 ./travel_guides/berlitz2/Costa-History.txt
60376721   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14889 Feb  7 21:16 ./travel_guides/berlitz2/Costa-WhatToDo.txt
60376722   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73708 Feb  7 21:16 ./travel_guides/berlitz2/Costa-WhereToGo.txt
60376723   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11981 Feb  7 21:16 ./travel_guides/berlitz2/CostaBlanca-History.txt
60376724   36 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    30453 Feb  7 21:16 ./travel_guides/berlitz2/CostaBlanca-WhatToDo.txt
60376725   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    15760 Feb  7 21:16 ./travel_guides/berlitz2/Crete-History.txt
60376726   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    16532 Feb  7 21:16 ./travel_guides/berlitz2/Crete-WhatToDo.txt
60376727   84 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    81548 Feb  7 21:16 ./travel_guides/berlitz2/Crete-WhereToGo.txt
60376728   52 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    48636 Feb  7 21:16 ./travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
60376729   12 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    11789 Feb  7 21:16 ./travel_guides/berlitz2/Cuba-History.txt
60376730   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    17210 Feb  7 21:16 ./travel_guides/berlitz2/Cuba-WhatToDo.txt
60376731   80 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    76041 Feb  7 21:16 ./travel_guides/berlitz2/Cuba-WhereToGo.txt
60376733   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    18933 Feb  7 21:16 ./travel_guides/berlitz2/Nepal-History.txt
60376734   44 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    40450 Feb  7 21:16 ./travel_guides/berlitz2/Nepal-WhatToDo.txt
60376735   60 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    53280 Feb  7 21:16 ./travel_guides/berlitz2/Nepal-WhereToGo.txt
60376736   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    20746 Feb  7 21:16 ./travel_guides/berlitz2/NewOrleans-History.txt
60376737   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13871 Feb  7 21:16 ./travel_guides/berlitz2/Paris-WhatToDo.txt
60376738   76 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    73204 Feb  7 21:16 ./travel_guides/berlitz2/Paris-WhereToGo.txt
60376739   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    20387 Feb  7 21:16 ./travel_guides/berlitz2/Poland-History.txt
60376740   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    19408 Feb  7 21:16 ./travel_guides/berlitz2/Poland-WhatToDo.txt
60376741   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14604 Feb  7 21:16 ./travel_guides/berlitz2/Portugal-History.txt
60376742   20 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    17125 Feb  7 21:16 ./travel_guides/berlitz2/Portugal-WhatToDo.txt
60376743  124 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23   119651 Feb  7 21:16 ./travel_guides/berlitz2/Portugal-WhereToGo.txt
60376744   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    13736 Feb  7 21:16 ./travel_guides/berlitz2/PuertoRico-History.txt
60376745   28 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    20609 Feb  7 21:16 ./travel_guides/berlitz2/PuertoRico-WhatToDo.txt
60376746   72 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    66550 Feb  7 21:16 ./travel_guides/berlitz2/PuertoRico-WhereToGo.txt
60376747   16 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    14266 Feb  7 21:16 ./travel_guides/berlitz2/Vallarta-History.txt
60376748   40 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    36255 Feb  7 21:16 ./travel_guides/berlitz2/Vallarta-WhatToDo.txt
60376749   56 -rwxr-x---   1 cs15lwi23aqg ieng6_cs15lwi23    52679 Feb  7 21:16 ./travel_guides/berlitz2/Vallarta-WhereToGo.txt
```
- Here, the output displays every file in `./written_2` because they were all modified less than 7 days ago. This is because I imported these files less than 7 days ago, hence why the last modified date is February 7 21:16 as displayed.

- `find -mtime` Command Input - Example 2
```
$ find -mtime +9 -ls
```
- Output
```

```
- Here, no files in `./written_2` are displayed because none of these files were modified over 9 days ago.
---
4. `find -iname`
- `-iname` finds a files that matches with the following pattern. It is similar to `-name`, but it is case insensitive.
- For example, `CuBA-HiStOrY.tXt` will work with `-iname`, but it will not work with `-name`.
- This is useful because it helps the user avoid the hassle of case sensitive names of files when locating them!

- `find -iname` Command Input - Example 1
```
$ find -iname CuBA-HiStOrY.tXt
```
- Output
```
./travel_guides/berlitz2/Cuba-History.txt
```
- Here, the file `Cuba-History.txt` in `./written_2` is displayed/found because the command is not case sensitive.

- `find -iname` Command Input - Example 2
```
$ find -iname ALGARVe-HiStoRY.txT
```
- Output
```
./travel_guides/berlitz2/Algarve-History.txt
```
- Here, the file `Algarve-History.txt` in `./written_2` is displayed/found because the command is not case sensitive.
---
- All of command-line options/alternative ways to use `find` were found through the terminal's manual in the command `man find`.
