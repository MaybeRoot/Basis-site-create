# Michelin&Co — Сайт автосервиса

Сайт автосервиса с шиномонтажем в Ростове-на-Дону. Включает информацию об услугах, отзывы клиентов и систему онлайн-записи.


## 🛠 Технологии
- **HTML5** (семантическая верстка)
- **CSS3** (кастомные стили + Bootstrap Grid)
- **Yandex Maps API** (интеграция карты)
- **Google Fonts** (шрифт Noto Sans)
- **Адаптивный дизайн**

## 🌐 Структура сайта
- michelin-co/
  - css
     - styles.css # Стиль главной страницы
     - styles2.css # Стиль страницы записи
     - styles3.css # Стиль страницы уведомления
  - libs/                # Внешние библиотеки
  - img/                 # Все изображения
  - index.html           # Главная страница
  - success.html         # Страница уведомления
  - appointment.html     # Страница записи

## 🎯 Особенности
- **Интерактивная карта** с расположением сервиса
  - Настройка Яндекс.Карт
    1. Получить API-ключ [Янлекс.Разработчик](https://developer.tech.yandex.ru/services)
    2. Заменить в *index.html* :
       ```html
          <script src="https://api-maps.yandex.ru/2.1/?load=Geolink&amp;lang=ru_RU&amp;apikey=<полученный api-ключ>" type="text/javascript"></script>
       ```
- **Адаптивное меню** (работает на мобильных устройствах)
- **Карточки услуг** с ценами и описанием
- **Секция отзывов** с реальными комментариями клиентов
- **Система онлайн-записи** (переход на appointment.html)
