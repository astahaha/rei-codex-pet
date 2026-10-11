# Rei — Codex Pet

Рей Аянами в пиксельном стиле 32-битных игр. Это пользовательский питомец для Codex, собранный в формате sprite atlas v2.

![Спрайт-лист Rei](spritesheet.png)

## Файлы

- `pet.json` — описание питомца и версия формата атласа.
- `spritesheet.png` — прозрачный PNG, 1536 × 2288 px.

## Установка в Codex CLI

Питомцы доступны в поддерживаемых интерактивных терминалах. Для установки скопируйте папку `rei` в каталог пользовательских питомцев Codex:

```bash
mkdir -p "$HOME/.codex/pets/rei"
curl -L "https://github.com/astahaha/rei-codex-pet/archive/refs/heads/main.zip" -o /tmp/rei-codex-pet.zip
unzip -o /tmp/rei-codex-pet.zip -d /tmp/rei-codex-pet
cp /tmp/rei-codex-pet/rei-codex-pet-main/pet.json "$HOME/.codex/pets/rei/pet.json"
cp /tmp/rei-codex-pet/rei-codex-pet-main/spritesheet.png "$HOME/.codex/pets/rei/spritesheet.png"
```

Перезапустите Codex CLI, откройте интерактивный сеанс и выберите питомца через `/pets` или `/pet`.

## Совместимость

Этот репозиторий содержит Codex sprite atlas v2 размером 1536 × 2288. Загрузка пользовательского питомца в ChatGPT web использует отдельный формат: прозрачный PNG или WebP размером ровно 1536 × 1872 px. Этот файл напрямую для загрузки в ChatGPT web не подходит.

Питомцы в Codex IDE extension не поддерживаются; используйте Codex CLI или приложение ChatGPT для поддерживаемых возможностей питомцев. Подробности зависят от версии приложения и терминала. См. [официальную документацию Pets](https://learn.chatgpt.com/docs/pets).

## Авторские права

Рей Аянами — персонаж Neon Genesis Evangelion. Это неофициальная фанатская работа; права на персонажа и исходные элементы принадлежат их правообладателям. Репозиторий не предоставляет лицензию на эти элементы.
