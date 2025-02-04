---
title: Сведения о полях даты
shortTitle: About date fields
intro: Вы можете создавать настраиваемые поля дат, которые можно задать, введя дату или используя календарь.
miniTocMaxHeadingLevel: 3
versions:
  feature: projects-v2
type: tutorial
topics:
- Projects
ms.openlocfilehash: 7c3bc45c036e209e0be682c3b13b9dafcba17885
ms.sourcegitcommit: f638d569cd4f0dd6d0fb967818267992c0499110
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/25/2022
ms.locfileid: "148110062"
---
Вы можете отфильтровать значения даты с помощью формата `YYYY-MM-DD`, например: `date:2022-07-01`. Можно также использовать операторы, такие как `>`, `>=`, `<`, `<=` и `..`. Например, `date:>2022-07-01` и `date:2022-07-01..2022-07-31`. Вы также можете указать `@today`, чтобы обозначить текущий день в фильтре. Дополнительные сведения см. в статье [Фильтрация проектов](/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/filtering-projects).

## Добавление поля даты

{% data reusables.projects.new-field %}
1. Выберите **Дата**
   ![Снимок экрана: параметр "Дата"](/assets/images/help/projects-v2/new-field-date.png)
1. Выберите команду **Сохранить**.
   ![Снимок экрана: кнопка "Сохранить"](/assets/images/help/projects-v2/new-field-save.png)

Или откройте палитру команд проекта, нажав {% data variables.projects.command-palette-shortcut %}, и начните вводить "создать поле".
