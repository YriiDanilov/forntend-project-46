### Hexlet tests and linter status:
[![Actions Status](https://github.com/YriiDanilov/frontend-project-46/workflows/hexlet-check/badge.svg)](https://github.com/YriiDanilov/frontend-project-46/actions)

### Node CI:
[![Actions Status](https://github.com/YriiDanilov/My-second-project-on-Hexlet/actions/workflows/nodejs.yml/badge.svg)](https://github.com/YriiDanilov/frontend-project-46/actions)

### Maintainability Badge:
[![Maintainability](https://api.codeclimate.com/v1/badges/34098306c90c24446481/maintainability)](https://codeclimate.com/github/YriiDanilov/frontend-project-46/maintainability)

### Test coverage: 
[![Test Coverage](https://api.codeclimate.com/v1/badges/34098306c90c24446481/test_coverage)](https://codeclimate.com/github/YriiDanilov/frontend-project-46/test_coverage)

# Вычислитель отличий

### Описание

**Вычислитель отличий** - программа, определяющая разницу между двумя структурами данных. Это популярная задача, для решения которой существует множество онлайн сервисов, например http://www.jsondiff.com/. Подобный механизм используется при выводе тестов или при автоматическом отслеживании изменений в конфигурационных файлах.

#### Возможности утилиты:

- [x] Поддержка разных входных форматов: yaml, json
- [x] Генерация отчета в виде plain text, stylish и json

### Требования: 

Требуется [node.js](https://nodejs.org/en) версия 13.2.0 и выше (проверить версию установленной node возможно командой в терминале node -v)

### Установка:  

1. Клонируйте репозиторий с помощью следующей команды:

```
git clone https://github.com/YriiDanilov/frontend-project-46.git

```
2. Выполните команду: 

```
sudo npm link

```
Вызов справочной информации 

[![asciicast](https://asciinema.org/a/594504.svg)](https://asciinema.org/a/594504)

Пример работы с плоскими JSON файлами :

[![asciicast](https://asciinema.org/a/593064.svg)](https://asciinema.org/a/593064)

Пример работы с плоскими YAML файлами :

[![asciicast](https://asciinema.org/a/593282.svg)](https://asciinema.org/a/593282)

Пример работы с вложенными объктами :

[![asciicast](https://asciinema.org/a/594507.svg)](https://asciinema.org/a/594507)

Пример работы формата Plain: 

[![asciicast](https://asciinema.org/a/595517.svg)](https://asciinema.org/a/595517)

Вывод в формате JSON:

[![asciicast](https://asciinema.org/a/595530.svg)](https://asciinema.org/a/595530)

