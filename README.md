# SolidWorks Macros

## 🇷🇺 Описание
Набор макросов для автоматизации работы в SolidWorks:

- экспорт Cut List в STEP
- формирование структуры файлов
- генерация Excel отчётов
- расчёт веса

---

## 🇬🇧 Description
Collection of SolidWorks automation macros:

- export Cut List to STEP
- automatic file structure generation
- Excel report creation
- weight calculation

---

## 🚀 Current Tool

### Cut List to STEP

## 📸 Screenshots

### Excel Report
![Excel](Cut_List_to_STEP/screenshots/excel_report.png)

### STEP Structure
![Structure](Cut_List_to_STEP/screenshots/step_structure.png)

### STEP Files
![STEP](Cut_List_to_STEP/screenshots/step_files.png)

Макрос для:
- экспорта элементов weldment в STEP
- автоматического именования файлов
- создания Excel отчета

---

## 📦 Версия

**v2.2 (STABLE)**

---

## 📁 Структура проекта

```
Cut_List_to_STEP/
├─ src/
│  └─ Cut_List_to_step_v2_2_STABLE.swp
```
---

## 🔄 Changelog

### v2.2 (STABLE)
- исправлен расчет веса
- добавлено округление
- стабильная версия

### v2.0
- добавлен Excel отчет
- добавлена генерация STEP

### v1.0
- базовый экспорт STEP

---

## 🧑‍💻 Автор

Evgeniy (xd5oggy)

---

## 🗺️ Roadmap

### 🔵 v2.3 (DEV - in progress)
- [ ] Расчёт закупки (оптимизация под 6000 мм)
- [ ] Группировка одинаковых профилей
- [ ] Автоопределение типа профиля (Tube / L Angle / etc.)

---

### 🟢 v3.0 (NEXT)
- [ ] Обработка сборок (Assembly Cut List)
- [ ] Сбор Cut List со всех деталей в сборке
- [ ] Объединение данных в один Excel отчет
- [ ] Учет одинаковых деталей из разных компонентов

---

### 🟡 v3.5 (FUTURE)
- [ ] Оптимизация раскроя (минимизация отходов)
- [ ] Расчет остатков (waste)
- [ ] Подготовка данных для закупки материала

---

### ⚙️ Long-term
- [ ] UI (форма ввода параметров)
- [ ] Настройки (длина заготовки, типы профилей)
- [ ] Интеграция с производственным процессом
