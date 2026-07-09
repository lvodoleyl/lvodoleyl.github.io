# 🚀 Быстрый Старт - Академический Сайт

## ✅ Что уже сделано:

1. ✅ Установлена тема al-folio (популярная академическая тема Jekyll)
2. ✅ Настроена базовая конфигурация для lvodoleyl.github.io
3. ✅ Созданы все необходимые страницы:
   - About (главная с новостями)
   - Research & Publications
   - Education & Work Experience (с раскрывающимися элементами)
   - Teaching & Mentoring (с раскрывающимися элементами)
4. ✅ Настроена система новостей
5. ✅ Подготовлены шаблоны для социальных ссылок

## 📝 Что нужно сделать СЕЙЧАС:

### 1. Обновите свою информацию (10-15 минут)

#### Файл: `_data/socials.yml`
```yaml
email: your.email@example.com           # ← ЗАМЕНИТЕ на свой email
scholar_userid: YOUR_GOOGLE_SCHOLAR_ID  # ← ЗАМЕНИТЕ на ваш Google Scholar ID
```

#### Файл: `_pages/about.md`
- Замените "Your Institution" на название вашего университета
- Добавьте свою биографию
- Опишите исследовательские интересы
- Обновите контактную информацию

#### Файлы: `_pages/publications.md`, `_pages/experience.md`, `_pages/teaching.md`
- Замените placeholder текст на свою реальную информацию
- Добавьте свои публикации
- Добавьте образование и опыт работы
- Добавьте информацию о преподавании (если есть)

### 2. Добавьте файлы (5 минут)

```bash
# Скопируйте свое фото профиля
cp /путь/к/вашему/фото.jpg assets/img/prof_pic.jpg

# Скопируйте CV
cp /путь/к/вашему/cv.pdf assets/pdf/cv.pdf
```

### 3. Опубликуйте на GitHub (5 минут)

```bash
# Перейдите в директорию проекта
cd ~/research/web_site_KA

# Инициализируйте git (если еще не сделано)
git init

# Добавьте все файлы
git add .

# Сделайте коммит
git commit -m "Initial commit: Academic website setup"

# Создайте репозиторий на GitHub:
# Зайдите на https://github.com/new
# Название: lvodoleyl.github.io (ТОЧНО ТАК!)
# Тип: Public
# НЕ добавляйте README, .gitignore или license

# Подключите remote и загрузите код
git remote add origin https://github.com/lvodoleyl/lvodoleyl.github.io.git
git branch -M main
git push -u origin main
```

### 4. Активируйте GitHub Pages (2 минуты)

1. Зайдите в настройки репозитория:
   `https://github.com/lvodoleyl/lvodoleyl.github.io/settings/pages`

2. В разделе "Source":
   - Branch: `main`
   - Folder: `/ (root)`
   - Нажмите **Save**

3. Подождите 3-5 минут

4. Откройте: **https://lvodoleyl.github.io**

## 🎉 Готово!

Ваш сайт будет доступен по адресу: **https://lvodoleyl.github.io**

## 📚 Дополнительная Информация

- **Детальная инструкция**: `SETUP_INSTRUCTIONS.md` (на английском)
- **Краткое описание**: `README_RU.md` (на русском)
- **Документация al-folio**: https://github.com/alshedivat/al-folio

## 🔄 Как обновлять сайт?

После публикации, для обновления сайта:

```bash
# Внесите изменения в файлы
# Затем:
git add .
git commit -m "Описание изменений"
git push
```

GitHub автоматически пересоберет сайт через 2-5 минут.

## ❓ Возникли проблемы?

1. Проверьте вкладку "Actions" в вашем репозитории на GitHub
2. Убедитесь, что название репозитория точно: `lvodoleyl.github.io`
3. Проверьте настройки GitHub Pages (шаг 4 выше)
4. Очистите кэш браузера или используйте режим инкогнито

## 💡 Полезные Советы

- **Новости**: Добавляйте файлы в `_news/` для обновления новостной ленты
- **Фото**: Оптимизируйте фото профиля (рекомендуется 400x400px)
- **CV**: Держите CV актуальным, просто заменяйте файл `assets/pdf/cv.pdf`
- **Темы**: Пользователи могут переключаться между светлой/темной темой

---

**Удачи! Если что-то непонятно, читайте `SETUP_INSTRUCTIONS.md` 🎓**
