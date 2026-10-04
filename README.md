# Kickbag-PowerApp

Ein Programm, welches ich mit Microsoft Power Apps erstellt habe, um den internen Ablauf zu erleichtern.

> Jahr: 2024–2026

> Plattform: Windows

> IDE: Microsoft Power Platform (Power Apps & Power Automate)

> Programmiersprache: PowerFX

## Das Projekt

Als wir im Onlineshop mit den Kickbags angefangen haben, mussten unsere Verpacker für die drei unterschiedlichen Grössen je einen Strich auf ein Blatt Papier machen für jeden benutzten Kickbag.
Diese gaben sie uns dann am Ende des Arbeitstages wieder zurück, um sie zu zählen.
Leider gab es aber oft Probleme mit verlorenen Zetteln oder fehlender Zeit beim Eintragen.
Somit gingen einige unter.

Ich hatte eines Tages die Idee, mir Power Apps zunutze zu machen.
Somit begann die Idee, die Strichliste abzuschaffen, zu digitalisieren und zu automatisieren.

## Das Programm

Die Power App lässt sich einfach im Webbrowser als App installieren.
Der Nutzer/Verpacker öffnet die Web-App neben dem Verpackungsfenster und kann den entsprechenden Knopf drücken.

Es hat jeweils zwei Knöpfe pro Grösse.
Einen zum Zählen und einen zum Löschen.
Das UI habe ich so schlicht wie möglich erstellt, um eine klare Übersicht zu schaffen.

Drückt man nun den +1-Knopf von z. B. der Grösse "S", wird im Hintergrund ein Power Automate Flow ausgeführt, welcher gleich einen Eintrag in eine in Teams hinterlegte Excel-Datei schreibt.

In dieser Excel-Datei landen alle Einträge vom aktuellen Tag.
Grösse, Nutzer und Zeitstempel sind einsehbar für allfällige Rückschlüsse bei Fehlern.

Am Ende des Tages wird durch einen Power Automate Flow die komplette Liste gezählt und zur Übersicht in eine weitere Auswertungsliste eingetragen.

Die Tagesübersicht wird anschliessend gereinigt und unsere E-Commerce-Zentrale bekommt eine automatisierte Mail, in der zusammengefasst steht, welcher der drei Onlineshops pro Tag wie viele Kickbags von welcher Grösse versendet hat.

## Abschlussnotiz

Durch meinen Einsatz konnten wir eine sehr gute Lösung finden, welche von allen Mitarbeitern geschätzt wurde.
Sie ermöglichte das einfache Eintragen, Bestellen und Analysieren der Nutzung.

Das Projekt wurde schliesslich vor einigen Monaten im Jahr 2026 durch die Auflösung des Vertrages mit der Post/Kickbag eingestellt.
Die Erfahrung, die ich durch mein erstes richtiges Power-Apps-Programm damit sammeln konnte, half mir sehr, mich tiefer damit zu befassen, und war ausserdem ein grosser Bestandteil meiner folgenden Programme für das Unternehmen.
