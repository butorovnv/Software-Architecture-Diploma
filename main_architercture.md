# Базовая архитектура с учётом ограничений бизнес-требований, НФТ, выбранной архитектуры, адресация атрибутов качества

Финальный вид архитектуры:
Представленная здесь схема реализует микросервисную архитектуру, где основные микросервисы общаются между собой по REST интерфейсам, за исключением Message микросервиса (KWT протоклок Kafka).

Каждое архитектурное решение формируется постепенно, проходя ряд итерационных изменений, дискуссий, компромиссов и тд. Концептуальная архитектура, предложенная на картинке - предварительный вариант, вероятно, отличающийся от итогового решения, т.к процессе практической реализации могут возникать непредвиденные аспекты и технические/бизнес ограничени, требующие оперативного разрешения. Желательно выявлять такие сложности заранее, а не на финальной стадии проекта, поскольку позднее обнаружение проблем способно привести к полному пересмотру и переработке всех созданных моделей и структуры системы вместе с сопутствующими рисками и затратами.

![Main_architecture](https://github.com/butorovnv/Software-Architecture-Diploma/blob/main/images/Main_architecture.png)

