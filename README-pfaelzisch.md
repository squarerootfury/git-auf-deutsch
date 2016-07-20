# Git auf Deutsch (Pfälzisch)

Die dägliche Kommunigation in deutsche Endwicklungteams, wo ma `git` (des heeßt so viel wie `Dummkopp`) 
anwent, is halt oft es feinschde Denglisch.
_"Kannsch du mol pulle"_ orer _"hasch du schunn jepuschd"_ sin nur zwee vun denne seltsam klingende ausdrick.

Git uf deutsch (Pfälzisch) schafft do abhilfe!

## Vorschläche

Nu folgchen zwee Tabellen mit de Vorschlechen für den tächlichen Gebrauch.

| Verb        | Aktueller Jebrauch | Vorschlach             |
|-------------|--------------------|------------------------|
| pull        | pullen             | ziehn                   |
| push        | pushen             | drigge                |
| fetch       | fetchen            | herschaffe                  |
| branch      | branchen           | abbieche            |
| commit      | commiten           | ableche              |
| rebase      | rebasen            | umschreibe            |
| merge       | mergen             | zammebringe         |
| stash       | stashen            | bunkern             |
| tag         | tagen              | margiere              |
| cherry-pick | cherry-picken      | die rosine rausplicke |

| Substantiv   | Aktueller jebrauch | Vorschlach     |
|--------------|--------------------|---------------|
| git          | git                | dummbeitel   |
| repository   | repo               | vereinsheim   |
| branch       | branch             | zweich         |
| commit       | commit             | ableche      |
| pull request | pull request       | nemmunhalldeigosch  |
| stash        | stash              | buchte      |
| tag          | tag                | margierung    |

## Beispiele

    - Kannste de den Zweich, den ich gerade umgeschribb hann, zern un nach github drigge?

    - Ich hawve gerade abgeboche und de Änderungen aus meiner buchte abgeleecht.

    - Mache een nemmunhalldeigosch, wenn de mit dem zammebringe fertich bisch!

    - Am beschde wir plicke uns die rosine dem Meisterzweeg raus.

## Git auf Deutsch (Pfälzisch) anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf Deutsch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den 
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig` 
vor:

    git config --global alias.ziehn pull
    git config --global alias.drigge push
    git config --global alias.zweich branch
    git config --global alias.ableche commit
    git config --global alias.umschreibe rebase
    git config --global alias.zammebringe merge
    git config --global alias.bunkern stash
    git config --global alias.margiere tag

    alias dummbeitel=git
