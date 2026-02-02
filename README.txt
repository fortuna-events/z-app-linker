usage: linker.py [-h] [--with-debug] [-f] [-p] [--dry] [-d [data.txt]]

links z-app data between them.
(see data.sample.txt for data format)
separators:
===== https://app.fortuna-events.fr
@@@@@ https://treasure.fortuna-events.fr
????? https://quizz.fortuna-events.fr
+++++ https://roads.fortuna-events.fr
%%%%% https://dice.fortuna-events.fr
$$$$$ https://quest.fortuna-events.fr

options:
  -h, --help            show this help message and exit
  --with-debug          create debug Cross-Roads link with all links within
  -f, --fast            resolve links in dependency order (faster)
  -p, --preview         show links tree in a preview.png file
  --dry                 do not compute links
  -d [data.txt], --data [data.txt]
                        data file path (default: data.txt)