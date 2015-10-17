# MacOS X #

## Vorbereitung ##
  * Python 2.5.4 installieren (http://www.python.org/download/releases/2.5.4)
  * libjepg downloaden, entpacken und installieren ([jpegsrc.v6b.tar.gz](ftp://ftp.uu.net/graphics/jpeg/jpegsrc.v6b.tar.gz))
```
    % cd jpeg-6b/
    % ln -s `which glibtool` ./libtool
    % setenv MACOSX_DEPLOYMENT_TARGET 10.4
    % ./configure --enable-shared && make && sudo make install
```
  * PIL (Python Imaging Library) 1.1.6 installieren (http://pythonmac.org/packages/py25-fat/dmg/PIL-1.1.6-py2.5-macosx10.4-2007-05-18.dmg)
  * Numpy installieren (http://numpy.scipy.org)
  * BierBot downloaden

Die meisten Downloads zu den obigen Paketen findet man auch hier:
http://pythonmac.org/packages/py25-fat/

## Installation ##
  * BierBot ZIP-Datei auspacken, evtl. in ein Verzeichnis Deiner Wahl verschieben.

## BierBot starten ##
  * Terminal öffnen (Programme -> Dienstprogramme -> Terminal)
  * in das Verzeichnis von BierBot wechseln ('_cd_ _pfad/zum/BierBot_')
  * starten mit '_python_ _main.py_'