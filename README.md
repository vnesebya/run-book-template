# Run Book Шаблон

Руководство по эксплуатации для современных программных систем.

Есть два основных файла:

1. `run-book-template.md` - сам шаблон (см. Ниже)
2. `Диалоговый лист Run Book`https://github.com/SkeltonThatcher/run-book-template/releases/latest, PDF (300 КБ) с заголовками, взятыми из `run-book-template.md` и предназначен для печати на бумаге формата А1 для использования в командных условиях. _Диалоговый лист «Run Book» основан на работе над «Листами диалога» Аллана Келли] (https://www.infoq.com/articles/dialogue-sheets-retrospectives) и используется с его разрешения.

## Обзор

Файл `run-book-template.md` содержит рекомендуемые проверки и процедуры для большинства нетривиальных программных систем, которые можно использовать в качестве ** шаблона для создания Runbook или руководства по эксплуатации системы ** (SOM). Рассматривайте полученную информацию в качестве отправной точки для обсуждения эксплуатационной готовности.

По нашему опыту, наиболее интересным программным системам понадобятся инженеры для решения большинства вопросов, хотя бы для того, чтобы подтвердить, что «этот раздел определенно здесь не применим» - ценная реализация. В каждом разделе есть описание, чтобы установить контекст и объяснить, почему это необходимо.

Скорее всего, вы получите наилучшие результаты, если будете иметь собственную команду разработчиков программного обеспечения ** и будете руководить мероприятиями по Run Book **, запрашивая информацию от специалистов по тестированию и Ops, чтобы заполнить пробелы в знаниях. На практике вы захотите автоматизировать многие проверки и процедуры (вместо того, чтобы оставлять их в вики), но помните: в обсуждении Run Book стоит _discussion, а не то, что документация_! См. [Runbookcollab.info] (http://runbookcollab.info/) для более подробной информации.

Веселитесь! Матвей Скелтон и Роб Тэтчер

> В книге [Руководство для команд по работоспособности программного обеспечения] (http://operabilitybook.com/) есть глава, посвященная использованию совместной работы Run Book и диалоговому листу Run Book, в котором подробно рассказывается, как разные команды используют эти методы.
> <br/>
> <img src = "Team-Guide-to-Software-Operability.png" width = "200" />

Copyright © 2014-2016 [Скелтон Тэтчер Консалтинг] (https://skeltonthatcher.com/)

Лицензировано в соответствии с [CC BY-SA 4.0] (https://creativecommons.org/licenses/by-sa/4.0/)! [CC BY-SA 4.0] (https://licensebuttons.net/l/by-sa/). 3,0 / 88x31.png)

## Как использовать шаблон

1. Сделайте форк репозитария
1. Отредактируйте файл [`run-book-template.md`] (run-book-template.md)
1. Добавьте свои собственные проверки и проверки во время выполнения - отправьте нам запрос на извлечение, если вы считаете, что ваши новые проверки полезны для других!
1. Удалите (или прокомментируйте _N / A_) те разделы, которые действительно не применяются в вашем случае (но сначала проверьте еще раз).
1. Используйте шаблон как способ [поощрить обсуждение и сотрудничество между разработчиками (Dev) и командой эксплуатации (Ops) для создания более совершенных систем] (http://runbookcollab.info/).
1. Если какая-либо информация отсутствует для одного или нескольких разделов, четко укажите это (например, * ПРЕДУПРЕЖДЕНИЕ *). Знание того, чего вы не знаете, ценно.
1. После того, как вы проверили эксплуатационные аспекты со всеми вовлеченными командами, начните автоматизировать проверки и процедуры.

** Ожидайте редизайн частей программного обеспечения для лучшего удовлетворения эксплуатационных потребностей, изложенных в этом шаблоне! **
