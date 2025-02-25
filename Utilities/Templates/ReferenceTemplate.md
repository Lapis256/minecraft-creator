---
author: YOUR MS ACCOUNT NAME
ms.author: YOUR MS ACCOUNT NAME
title: NAME OF THE REFERENCE SUBJECT
ms.prod: gaming
description: BRIEF SUMMARY OF THE REFERENCE SUBJECT
---
# [NAME OF THE REFERENCE SUBJECT]

`Intro Text` for your reference subject. Make sure to use code blocks when referring to entities, components, or other code-based reference subject by name. Briefly describe what this entity, component, or tool does and what effect it has on players or the Minecraft World.

> [!NOTE]
> You should generally refrain from step-by-step tutorials in reference documentation. If there is a specific use case for your reference subject, consider writing a [tutorial](TutorialTemplate.md).

>[!IMPORTANT]
> Any behaviors, settings, or considerations that creators must implement for things to work properly should be called out in an [!IMPORTANT] section.

## [SECTION HEADER]

Sections can be used to detail parameters of JSON objects or other characteristics of the reference subject.

> [!NOTE]
> All section headers should be H2's (##) and all subsections should follow the appropriate hierarchy. The only H1 (#) should be the article title, which should match the title in the metadata.

Here is a sample table for a JSON object reference:

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|Parameter |*not set* |string |This is an example of a parameter. |

### [SUBSECTION HEADER]

[SUBSECTION TEXT]

> [!NOTE]
> Subsections (H3's and lower) will not be listed or linked in the article Table of Contents on MS Docs. You can manually link to subsections, but keep this in mind as it can make navigating your tutorial difficult if subsections are overly long.

> [!IMPORTANT]
> Use as many sections and subsections as you need to complete your tutorial, but do not drill down further than H4's (####), and try to use those sparingly.

Here is how you can sample code from other reference docs:

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/ravager.json" range="298-333":::

Enter the relative path to the reference doc you want to sample into `source` and enter the line numbers you want to display in `range`.

## Vanilla entities using [REFERENCE SUBJECT]

- [ravager](../../../../Source/VanillaBehaviorPack_Snippets/entities/ravager.md)
