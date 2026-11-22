---
layout: post
title: "Hallo Welt! Mein erster Blogpost mit ChatGPT und Codex"
description: "Ein Selbstversuch mit ChatGPT, Codex, Jekyll und GitHub Pages."
---

Hallo Welt! Mit diesem Beitrag will ich ausprobieren, wie sich Bloggen mit meiner neuen Toolchain anfühlt. Kann ich ChatGPT einfach erzählen, worüber ich schreiben möchte, und kurz darauf einen Blogpost lesen, der schon im richtigen Format in meinem Repository liegt? Genau das teste ich hier.

## Was unter der Haube steckt

Die Inhalte liegen als Markdown-Dateien in meinem GitHub-Repository `greenacid/greenacid.github.io`. Jekyll baut daraus eine statische Website. Titel und Layout stehen oben in der Datei, und Jekyll setzt den Text in die Vorlage ein. Beim selben Build entstehen auch die Startseite mit der Beitragsliste und der RSS-Feed.

GitHub Pages ist so eingerichtet, dass es die Website aus dem `master`-Branch baut und veröffentlicht. Die eigene Domain `blog.3wfx.de` ist über die `CNAME`-Datei hinterlegt. In der Jekyll-Konfiguration steht die HTTPS-Adresse des Blogs, damit Seiten und Feed auf dieselbe Domain verweisen. GitHub Pages leitet HTTP-Aufrufe auf HTTPS um.

## Wie aus einer Idee ein Beitrag wird

Ich fange mit einer Idee an und erkläre sie ChatGPT, dem Sprachmodell-basierten Assistenten von OpenAI. Ich sage, worum es gehen soll, welche Details reinmüssen und wie der Text klingen soll. Daraus entsteht ein Entwurf. Codex übernimmt die Arbeit am Repository und legt den Text als Markdown-Datei an. Ich kann ihn in Ruhe lesen und Änderungen anstoßen, bevor er veröffentlicht wird.

An dieser Stelle bin ich gerade mit diesem Hallo-Welt-Post. Sobald ich mit dem Text zufrieden bin, kann der Entwurf in den Beitragsordner `_posts` wandern. Wenn die Änderung in `master` landet, baut GitHub Pages die Website neu. Danach ist der Beitrag auf dem Blog und im RSS-Feed zu finden.

## Was sich beim Schreiben verändert

Für mich ist das Schreiben damit unglaublich einfach geworden. Ich kann meine Gedanken so erzählen, wie sie mir gerade einfallen. Ich muss sie weder abtippen noch beim Erzählen schon am Satzbau feilen. ChatGPT bringt die Gedanken in eine lesbare Reihenfolge, und ich entscheide beim Gegenlesen, ob der Text sagt, was ich sagen wollte.

Ob daraus regelmäßig gute Beiträge werden, muss sich noch zeigen. Aber die Hürde, eine Idee überhaupt als Blogpost festzuhalten, ist für mich deutlich kleiner geworden. Für einen Hallo-Welt-Post ist das schon mal ein guter Anfang.
