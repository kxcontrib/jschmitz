Kate (KDE) syntax highlighting files for the KDB languages q and k.

Created by James Schmitz (james.schmitz at gmail.com). Please contact me with bug reports.

Installation:

  On Linux, copy the q.qml and k.xml files to the directory:

    ~/.kde/share/apps/katepart/syntax

  Then (re)start Kate. Make customizations on the Settings -> Configure Kate... -> Editor Component -> Fonts & Colors -> [Normal Text Styles|Highlighting Text Styles] tabs. The Normal Text Styles determines the default styles to use for all languages. The Highlighting Text Styles tabs maps q or k code to the defaults, but can easily be customized and over-ridden. 

  You can find more information on Kate here:

    http://kate-editor.org/

  Documentation:

    http://docs.kde.org/stable/en/applications/kate/index.html

  Highlighting specifically is here:

    http://docs.kde.org/stable/en/applications/kate/config-dialog-editor.html#prefcolors

Thanks:

  I would like to thank Andrey Zholos for his useful feedback and tireless testing efforts.

  I would also like to give credit to Simon Garland for creating the vim syntax highlighting files. Although these highlighting files are not translations of those files and the highlighting features are not identical, I did consult vim for thoughts on how q and k highlighting should be done.

