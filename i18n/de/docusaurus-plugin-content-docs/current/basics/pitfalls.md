---
sidebar_position: 90
---

# 🟢 Fallen der LLMs

import Pitfalls from '@site/docs/assets/basics/pitfalls.svg';

<div style={{textAlign: 'center'}}>
  <Pitfalls style={{width:"100%",height:"300px",verticalAlign:"top"}}/>
</div>


LLMs sind extrem leistungsfähig, aber sie sind keineswegs perfekt. Es gibt viele Fallstricke, auf die du achten solltest, wenn du sie nutzt.

## Citing Sources

LLMs können in den meisten Fällen **keine genauen Quellenangaben** machen. Das liegt daran, dass sie keinen Zugang zum Internet haben und nicht genau wissen, woher ihre Informationen stammen. Sie erstellen häufig Quellen, die gut aussehen, aber völlig ungenau sind.

:::Hinweis
Strategien wie sucherweiterte LLMs (LLMs, die das Internet und andere Quellen durchsuchen können) können dieses Problem oft lösen
:::

## Bias

LLMs sind oft geneigt, stereotype Antworten zu geben. Selbst mit Sicherheitsvorkehrungen werden sie manchmal sexistische/rassistische/homophobe Dinge sagen. Sei vorsichtig, wenn du LLMs in verbraucherorientierten Anwendungen verwendest, und sei auch vorsichtig, wenn du sie in der Forschung einsetzt (sie können verzerrte Ergebnisse liefern).

## Halluzinationen

LLMs können Unwahrheiten produzieren, wenn ihnen eine Frage gestellt wird, deren Antwort sie nicht kennen. Manchmal geben sie an, dass sie die Antwort nicht wissen, aber meistens werden sie selbstbewusst eine falsche Antwort geben.

## Mathematik

LLMs sind oft schlecht in Mathe. Sie haben Schwierigkeiten, einfache mathematische Probleme zu lösen. Bei komplexen Aufgaben sind sie oft gar nicht in der Lage diese zu lösen.

:::Hinweis
Dieses Problem lässt sich bis zu einem gewissen Grad durch die Verwendung einer [Werkzeug-erweiterter LLM](https://learnprompting.org/docs/advanced_applications/mrkl).
:::

## Prompt Hacking

Benutzer können LLMs dazu bringen, beliebige Inhalte zu erstellen. Mehr darüber kannst du [hier](https://learnprompting.org/docs/category/-prompt-hacking) lesen.