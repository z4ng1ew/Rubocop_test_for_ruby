## 📄 **Описание проекта**

### 🇷🇺 **На русском:**

Проект на Ruby с использованием Bundler для управления зависимостями и RuboCop для статического анализа кода. Настроен автогенератор `.rubocop.yml` и автокоррекция кода. Отлично подходит для изучения чистого и идиоматичного Ruby-кода.

### 🇬🇧 **In English:**

Ruby project using Bundler for dependency management and RuboCop for static code analysis. Auto-generated `.rubocop.yml` and autocorrection are configured. Perfect for learning clean and idiomatic Ruby code.

---

## 📘 **README.md**

````markdown
# Ruby Linting Project with RuboCop

## 📌 Описание

Небольшой проект на Ruby, демонстрирующий:
- использование Bundler для управления зависимостями;
- применение RuboCop для анализа и автоисправления кода;
- создание собственного `.rubocop.yml` через `--auto-gen-config`.

---

## 🚀 Установка

> Требуется установленный Ruby (желательно через `apt` или `snap`).

### 1. Настройка окружения для пользователя:
```bash
echo 'export GEM_HOME="$HOME/.gem"' >> ~/.bashrc
echo 'export PATH="$HOME/.gem/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
````

### 2. Установка зависимостей:

```bash
gem install bundler
gem install rubocop
```

---

## 🧰 Использование

### Линтинг всех файлов:

```bash
rubocop
```

### Автогенерация конфигурации:

```bash
rubocop --auto-gen-config > .rubocop.yml
```

### Автоисправление ошибок:

```bash
rubocop -A
```

---

## 📁 Структура

```
my_ruby_project/
├── Gemfile
├── .rubocop.yml
└── app.rb
```

---

## 💡 Пример Gemfile

```ruby
source 'https://rubygems.org'

gem 'rubocop', require: false
```

---

## ✍️ Пример кода (app.rb)

```ruby
def hello
  puts "Hello, world!"
end

hello
```

---


