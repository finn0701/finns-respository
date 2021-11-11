title: "Mein Markdown Meilenstein"
author: "Finn Seybold"
date: "11/8/2021"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(
	message = FALSE,
	warning = FALSE,
	include = FALSE
)
```

# R Markdown erlernen
## Meine Erfahrungen mit diesem Meilenstein
Zu Beginn war es **sehr schwer** für mich, **R und R-Studios zu verstehen**. Allein das Interface war für mich sehr verwirrend, weil es so *umfangreich* ist und einem so *viele Möglichkeiten* zur Verfügung stehen. Außerdem wusste ich anfangs nicht, welche "Packages" ich installieren sollte. Nach einiger Zeit und genauem Studieren der Lernvideos und Buchkapitel, begann ich aber glückicherweise  durchzusteigen. Das Einfügen des GitHub-Bilds hat mir gegen Ende Probleme bereitet, aber nach kurzer Recherche und einigen Versuchen hat auch das funktioniert. 


### Mein Datenmanifest 
Ich weiß jetzt, dass meine Daten nicht nur mir gehören. Meine Daten werden online fast überall ergriffen. Sogenannte „Verhaltensüberschusslieferanten“ verarbeiten meine Daten in „New-Age-Fabriken“ zu „Vorhersageprodukten“ und verkaufen sie auf „Verhaltensterminkonraktmärkten“ an Unternehmen aller Sektoren. Es gibt also ein regelrechtes Ökosystem, in dem meine Daten erfasst und verkauft werden, um den monetären Gewinn der sogenannten „Überwachungskapitalisten“-Ökonomen aus verschiedenen Sektoren- in die Höhe zu treiben. Natürlich kann man dem entgegenwirken, indem man seinen Onlinekonsum einschränkt, manchmal ist das aber nicht möglich. Der Verzicht auf beispielsweise Social Media stellt für einen großen Teil der Bevölkerung eine Schwierigkeit dar. Schulen beispielsweise verlagerten ihren Unterricht in der Corona-Zeit ins Digitale. Wer keinen Zoom- oder Teams-Account hatte, der konnte nicht am Unterricht teilnehmen und hatte folglich größere Schwierigkeiten in der nächsten Klausur, sofern er überhaupt daran hätte teilnehmen können. In Bereichen wie Arbeit oder Bildung ist es also manchmal notwendig seine Daten preiszugeben und sie folglich in den Besitz anderer auszuhändigen.
Glücklicherweise weiß ich dank der digitalen Selbstschutz Serie, wie ich meine und andere Daten vor unerwünschtem Abgreifen schützen kann. Man sollte regelmäßige Back-Ups machen. Es ist am sinnvollsten auch externe Back-Ups zu besitzen, beispielsweise auf einer Cloud oder einer externen Festplatte. Außerdem sollte man regelmäßig Software-Hygiene betreiben. Alte Anwendungen können gelöscht werden und die, die man benutzt, sollte man immer auf dem aktuellen Stand halten (Updates). Des Weiteren ist es sinnvoll, lange Passwörter und einen Passwort-Manager zu verwenden. Wenn man auf Webseiten seine Daten eingibt, ist es wichtig zu überprüfen, ob die URL gesichert ist. Ist die URL gesichert, sollte man trotzdem überprüfen, ob das Sicherheits-Zertifikat von einer seriösen Institution/Organisation verliehen wurde. Auch bei WLAN-Netzwerken sollte man vorsichtig sein. Über öffentliche Hotspots kann unter Umständen auf die Daten, die sich auf verbundenen Geräten befinden, zugegriffen werden. Sie sollten daher gemieden werden. Auch über Emails kann ein Gerät von Schadsoftware angegriffen werden, weshalb man Mails, die ihren Namen nicht nennen und dringenden Handlungsbedarf ausdrücken, mit einer gewissen Grundskepsis entgegentreten sollte. 

#### Wem gehören meine Daten?

* mir
* "Verhaltensüberschusslieferanten"
* Ökonomen/ Überwachungskapitalisten

#### Wie kann ich meine Daten schützen?

1. Passwörter verlängern
2. URL-Sicherheit prüfen
      + gegebenenfalls Zertifikat prüfen
3. Öffentliche Hotspots meiden
4. Softwarehygiene betreiben 

##### Aufgabe: Wie lange muss ich arbeiten?

```{r Wie lange muss ich bis zur Rente arbeiten?}
geburt <- 2002 # bitte Geburtsjahr eingeben [YYYY eingeben]
alter <- 2021 - geburt
# wir berechnen Ihr Alter im Jahr 2020 (für das gesamte Jahr)
alter

# Wir berechnen Ihr Rentenalter und gehen davon aus, dass Sie mit 69 in  Rente gehen können.
rentenalter <- geburt + 69
rentenalter

# Wir gehen davon aus, dass Sie in drei Jahren anfangen werden zu arbeiten.
arbeitsbeginn <- 2023
arbeitsjahre <- rentenalter - arbeitsbeginn

# Voila: wenn alles klappt, arbeiten Sie so lange.
arbeitsjahre

```

###### Mein Bild aus Github

!
