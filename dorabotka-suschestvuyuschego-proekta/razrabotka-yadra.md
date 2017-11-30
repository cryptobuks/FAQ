# Разработка ядра

При выборе этого способа, необходимо создать в проекте трехзвенную архитектуру:

* API
* CORE
* UI

Так как UI проекты уже созданы, требуется лишь создать API \(будет отвечать за взаимодействие с сервером\) и CORE \(содержит всю бизнес-логику\) проекты типа Portable Class Library.
