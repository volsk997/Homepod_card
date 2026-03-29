# 🍄 Mushroom-Homepod_card

<img width="748" height="1186" alt="Снимок экрана — 2026-03-29 в 17 04 57" src="https://github.com/user-attachments/assets/8df23cc2-7ef1-4f34-b9a9-cb4b93229bf7" />


## Карта для Homepod на базе нескольких карт:
 1. [Mushrooms](https://github.com/piitaya/lovelace-mushroom)
 2. [Mini Media Player](https://github.com/kalkih/mini-media-player)
 3. [CardMod](https://github.com/thomasloven/lovelace-card-mod)
 4. [Bubble Card](https://github.com/Clooos/Bubble-Card) (в некоторых версиях)

> [!CAUTION]
> Для корректной работы требуется установка всех перечисленных компонентов, а так же [внешних шаблонов](https://github.com/volsk997/custom_templates)

> [!IMPORTANT]
> Карта построена на базе "Разделы"

> [!IMPORTANT]
> Заменить media_player.homepod на свою колонку

> [!IMPORTANT]
> [Файлы](https://github.com/volsk997/custom_templates) с расширением .jinja разместить в папке **/custom_templates**, после чего выполнить действие **action: homeassistant.reload_custom_templates**

> [!IMPORTANT]
> Для запуска музыки на бездейтсвующей колонке используется автоматизация внутри приложения "Дом (Apple Home)". При включении переключателя input_boolean.appletv_play_music запускается плейлист "Моя станция"
