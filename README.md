# Лабораторная работа 10. UML-моделирование и реинжиниринг

**Тема:** Университетская информационная система
**Выполнил:** Горбов Д. А. Группа 10

## Описание проекта
В рамках работы была спроектирована объектная модель университетской информационной системы, сгенерирован исходный код на Java, проведен реинжиниринг и построены поведенческие UML-диаграммы.

## Структура репозитория
- `/src` (или корень) — исходный код на Java.
- `/LabFiles` (или просто картинки в корне) — UML-диаграммы (Классов, Прецедентов, Активностей, Последовательностей).
- `/LabImages` — скриншоты успешного выполнения программы.

## UML Диаграммы
1. **Class Diagram** (Диаграмма классов) — отображает структуру системы, наследование (Employee -> ResearchAssociate -> Lecturer) и связи (композиция, агрегация).
![Class Diagram](LabImages/Class-diagram-before-compilation.png)
![Class Diagram](LabImages/Class-diagram-after-compilation.png)
2. **Use Case Diagram** (Диаграмма прецедентов) — показывает роли (Dean, Lecturer, Research Associate, Admin) и их цели.
![Use Case Diagram](LabImages/Use-case-diagram.png)
3. **Activity Diagram** (Диаграмма активностей) — алгоритм назначения курса с использованием дорожек (Swimlanes).
![Activity Diagram](LabImages/Activity-diagram.png)
4. **Sequence Diagram** (Диаграмма последовательностей) — сценарий вызова метода `assignCourse` с созданием объекта Course.

![Sequence Diagram](LabImages/Sequence-diagram.png)

## Как запустить
1. Скомпилируйте все `.java` файлы.
2. Запустите класс `AdministrativeEmployee.java`.