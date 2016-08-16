---
f1_keywords:
- samplef1keyword1
- samplef1keyword2
dev_langs:
- csharp
- fsharp
target_framework_moniker:
- Office.Version=v15
---

# How To Publish Content to Enable F1 Query

## Metadata Strategy
1. **f1_keywords** (_required_, _multivalue_): need to provide one or more F1 keywords for this content, which will be used to match the keywords from F1 query URL.

2. **dev_langs** (_required_, _multivalue_): the supported develop languages of this content. The F1 query will specify the dev_lang that the develop is currently using in the IDE. 


##YAML Header
The metadata is set in YAML header of the Markdown file of your content:

```md
f1_keywords:
- samplef1keyword1
- samplef1keyword2
dev_langs:
- csharp
- fsharp
target_framework_moniker:
- Office.Version=v15
version: 15
locale: en-us
```