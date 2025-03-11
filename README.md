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
          <iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3Aa7c769456d3efe691f764e5022ed5dfebca8593e2b100a034c69cd9a9930a69f&amp;source=constructor" width="760" height="400" frameborder="0"></iframe>
       ```
- **Адаптивное меню** (работает на мобильных устройствах)
- **Карточки услуг** с ценами и описанием
- **Секция отзывов** с реальными комментариями клиентов
- **Система онлайн-записи** (переход на appointment.html)
