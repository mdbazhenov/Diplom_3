# Дипломный проект по тестированию веб-приложения Stellar Burgers

## Описание проекта
Проект автоматизации тестирования веб-приложения Stellar Burgers. Включает в себя UI-тесты основного функционала сайта.

## Технологии
- Python 3.x
- Selenium WebDriver
- Pytest
- Allure Framework

## Структура проекта
Diplom_3/
├── pages/ # Page Object Models
│ ├── base_page.py # Базовый класс для страниц
│ ├── login_page.py # Страница авторизации
│ ├── feed_page.py # Страница ленты заказов
│ └── ...
├── tests/ # Тестовые файлы
│ ├── test_main_functionality.py
│ ├── test_order_feed.py
│ └── ...
├── locators.py # Локаторы элементов
├── conftest.py # Конфигурация тестов
└── README.md
