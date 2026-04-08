# puzzle-template
Коллекция готовых шаблонов для быстрой разработки автоматизаций в Puzzle RPA Studio

# Puzzle RPA Templates

Репозиторий с готовыми шаблонами для Puzzle RPA Studio.

Шаблоны позволяют быстро собирать автоматизации без необходимости писать процесс с нуля — достаточно выбрать подходящий шаблон и вставить его в проект.

---

## 🚀 Что внутри

В репозитории собраны шаблоны для типовых задач:



Каждый шаблон включает:
- описание (`readme.md`)
- мета-информацию (`meta.json`)
- превью (`preview.png`)
- JSON-описание блоков (`template.json`)

---

## 📂 Структура репозитория
templates/
├── categories.json
├── <category>/
│ ├── category.json
│ ├── templates.json
│ └── <template>/
│ ├── versions.json
│ └── <version>/
│ ├── template.json
│ ├── readme.md
│ ├── preview.png
│ └── meta.json
