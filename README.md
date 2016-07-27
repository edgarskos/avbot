------------------------------------------
 AVBOT (Anti-Vandalism BOT)
 Licencia: GPL v3
 Autor: emijrp (http://es.wikipedia.org/wiki/Usuario:Emijrp)
------------------------------------------

Se trata de un bot (script en python) que detecta vandalismos y otras ediciones maliciosas en artículos de Wikipedia en español en tiempo real y las revierte.

Requisitos para poder ejecutar el script (es multiplataforma):
* irclib
* pywikipediabot

Puede verlo funcionando en http://es.wikipedia.org/wiki/Especial:Contributions/AVBOT

# What is AVBOT?

*AVBOT* is an anti-vandalism bot for MediaWiki wikis. It is developed by [Emilio J. Rodríguez-Posada](https://github.com/emijrp ) in [Python](https://www.python.org), using pywikibot and irclib.

AVBOT has been working in [Spanish Wikipedia](http://es.wikipedia.org/wiki/Usuario:AVBOT) since 2008, it has reverted more than 250,000 vandalism edits, and it has [several clones](http://es.wikipedia.org/wiki/Usuario:AVBOT#Clones) managed by other users.

In 2009, this project was awarded with *Premio Nacional al "Mejor proyecto comunitario"* in the [http://www.concursosoftwarelibre.org/0809/premios-iii-concurso-universitario-software-libre III Concurso Universitario de Software Libre].
![AVBOT logo](/images/avbot-logo.png)

# Features

  * Regular expressions and scoring system
  * Blanking edits detector
  * Non-notable biographies detector for articles about years
  * Warning messages to vandals
  * Reporting of repetitive attacks to admins' noticeboard

# Download
You can download the *source code* from our [http://code.google.com/p/avbot/source/browse/#svn%2Ftrunk SVN repository].

# Documentation
In the [http://code.google.com/p/avbot/downloads/list downloads section] you can find a *manual* and other useful texts about AVBOT. There is also a *blog* at [http://avbot.blogspot.com avbot.blogspot.com].

# Publications

There are two main publications regarding AVBOT:

  * «[https://code.google.com/p/avbot/downloads/detail?name=III_2011_rodriguez1.pdf AVBOT: Detecting and fixing Vandalism in Wikipedia]». UPGRADE, Volume: 2011, Issue No. 3, July 2011.
  * «[https://code.google.com/p/avbot/downloads/detail?name=Rodriguez-nov203-vdef.pdf AVBOT: detección y corrección de vandalismos en Wikipedia]». NovATIca, núm. 203, 2010, pp. 51-53.

<a href="http://commons.wikimedia.org/wiki/File:Avbot_hasta_nov.svg"><img src="http://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Avbot_hasta_nov.svg/700px-Avbot_hasta_nov.svg.png" alt="Spanish Wikipedia vandalism edits reverted by AVBOT per day during 2008" title="Spanish Wikipedia vandalism edits reverted by AVBOT per day during 2008"/></a>

# Contribute
If you want to send any *suggestion*, reach me at [emijrp@gmail.com](mailto:emijrp@gmail.com). For *bugs*, you can use the [issues section](https://github.com/emijrp/avbot/issues). Thanks.
