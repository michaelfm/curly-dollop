---
layout: default
title: Startseite
nav_order: 1
---


# Startseite eines Ordners definieren

"index.md" nennen z.B. "docs/index.md"

# Dokumenation Theme 'Just the Docs'

https://pmarsceill.github.io/just-the-docs/docs/

# Sidebar Navigation definieren

https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/    

Folgende Anweisung am Anfang einer .md Datei definiert eine Unterseite in der Navigation. Da ist "parent" der Titel der übergeordneten Seite. Damit die übergeordnete Seite auch ausklappt, in jener, "has_childeren: yes" eintragen.

        ---
        layout: default
        title: 1.1
        parent: 1
        has_children: no
        ---
    
        
# Github Markdown

https://guides.github.com/features/mastering-markdown/
