---
created: 2024-06-29 15:34
modified: 2024-06-29T15:49:40-05:00
tags:
  - dataviewjstest
name: lorem ipsum
publish-ash: true
---

dataviewjs block outside of callout:
<span><span><p dir="auto">lorem ipsum</p></span></span>

> [!NOTE] Title
>  dataviewjs block with > character on each line
> <pre class="dataview dataview-error">Evaluation Error: SyntaxError: Unexpected token '&gt;'
    at DataviewInlineApi.eval (plugin:dataview:18869:21)
    at evalInContext (plugin:dataview:18870:7)
    at asyncEvalInContext (plugin:dataview:18880:32)
    at DataviewJSRenderer.render (plugin:dataview:18906:19)
    at DataviewJSRenderer.onload (plugin:dataview:18448:14)
    at e.load (app://obsidian.md/app.js:1:1166483)
    at DataviewApi.executeJs (plugin:dataview:19449:18)
    at DataviewCompiler.dataviewJS (plugin:obsidian-mkdocs-publisher:32:51054)
    at convertDataviewQueries (plugin:obsidian-mkdocs-publisher:35:1360)
    at async mainConverting (plugin:obsidian-mkdocs-publisher:44:1691)</pre>
>  dataviewjs block with > character only on first and last line of block
> <pre class="dataview dataview-error">Evaluation Error: SyntaxError: Unexpected token '&gt;'
    at DataviewInlineApi.eval (plugin:dataview:18869:21)
    at evalInContext (plugin:dataview:18870:7)
    at asyncEvalInContext (plugin:dataview:18880:32)
    at DataviewJSRenderer.render (plugin:dataview:18906:19)
    at DataviewJSRenderer.onload (plugin:dataview:18448:14)
    at e.load (app://obsidian.md/app.js:1:1166483)
    at DataviewApi.executeJs (plugin:dataview:19449:18)
    at DataviewCompiler.dataviewJS (plugin:obsidian-mkdocs-publisher:32:51054)
    at convertDataviewQueries (plugin:obsidian-mkdocs-publisher:35:1360)
    at async mainConverting (plugin:obsidian-mkdocs-publisher:44:1691)</pre>
> dataview block with > character on each line
>  | File                                                     | name        |
> | -------------------------------------------------------- | ----------- |
> | [[dataview test\|dataview test]] | lorem ipsum |
> 
> dataview block with > character only on first and last line
>  | File                                                     | name        |
> | -------------------------------------------------------- | ----------- |
> | [[dataview test\|dataview test]] | lorem ipsum |
> 
> 
> End of testing
