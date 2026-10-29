# FearSteamScan — Reverse Engineering Archive

[Русская версия ниже](#русский)

A public archive of static-analysis and reverse-engineering artifacts for **FearSteamScan**. It is intended to help security researchers investigate software behavior and assess potential security risks.

**Important:** These are reconstructed analysis artifacts, **not verified original developer source code**. Automated analysis and pseudocode may be incomplete or inaccurate.

## Download

[Download FearSteamScan_Sources.rar](./FearSteamScan_Sources.rar) (~7.7 MB)

**SHA-256:** `8766a2a5a60be4ae4a79768bb0ffd60b4915e03c2473fba4e6225e838f9dba8e`

## What's inside?

| Folder | Description |
| --- | --- |
| `01_reports/` | Security analysis reports and PE structural findings |
| `02_disassembly/` | Full disassembly (`ALL_TEXT.asm`) |
| `03_functions/` | Over 5,000 per-function assembly listings |
| `04_indexes/` | Function indexes in CSV and JSON |
| `05_pseudocode/` | Reconstructed sketches of the main flow and Steam/Discord/hardware collection and reporting routines |
| `06_strings/` | ASCII/UTF-16 strings and cross-references |
| `07_pe_metadata/` | PE section and import information and raw section contents |
| `08_tools/` | Recovery helper script |

The archive contains **5,083 entries**, including directories. The reconstructed pseudocode is not a substitute for independently verified source code.

## Research notes

- The archive is provided for defensive security research, software analysis, and reverse engineering.
- Treat all material as untrusted. Use an isolated environment for any analysis involving executable content.
- Findings are hypotheses derived from static analysis unless separately verified; they do not prove that any data was stolen or transmitted.
- Do not use these materials to access accounts, harvest credentials, or process data without authorization.
- No ownership or license claim is made over third-party code or binary fragments.

---

## Русский

Архив результатов статического анализа и реверс-инжиниринга **FearSteamScan** для специалистов по безопасности и исследователей ПО.

**Важно:** это **не подтверждённые оригинальные исходники разработчика**. В архиве находятся дизассемблированный код, псевдокод, метаданные PE и отчёты анализа. Автоматически восстановленные данные могут содержать ошибки.

### Что внутри

- `01_reports/` — отчёты и результаты анализа PE-файла
- `02_disassembly/` — полный дизассемблированный текст
- `03_functions/` — более 5 000 файлов с функциями
- `04_indexes/` — индексы функций в CSV и JSON
- `05_pseudocode/` — восстановленные схемы основного потока и процедур, связанных со Steam, Discord, оборудованием и отправкой отчётов
- `06_strings/` — извлечённые строки и перекрёстные ссылки
- `07_pe_metadata/` — секции и метаданные PE
- `08_tools/` — вспомогательный скрипт

### Назначение и безопасность

Материалы предназначены для исследования и защиты, а не для неправомерного доступа или кражи данных. Не запускайте неизвестные бинарные файлы на основной системе; используйте изолированную среду. Псевдокод и результаты статического анализа сами по себе не подтверждают факт кражи или передачи данных.
