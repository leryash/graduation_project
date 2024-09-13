# Анализ поведения пользователей в мобильном приложении по перепродаже вещей

**Цели исследования:**

- Управление вовлеченностью клиентов путем адаптации приложения под аудитории (целевую и смежную) на основе данных о поведении пользователей;
- Получить гипотезы об улучшении приложения с точки зрения пользовательского опыта на основе поведения пользователей.

**Задачи:**

- Проанализировать связь целевого события - просмотра контактов - и других действий пользователей:

    - *В разрезе сессий отобрать сценарии, которые приводят к просмотру контактов;* 
    - *Построить воронки по основным сценариям в разрезе уникальных пользователей*
    
    
- Оценить, какие действия чаще всего совершают те пользователи, которые просматривают контакты:

    - *Рассчитать относительную частоту событий в разрезе двух групп пользователей:*
        - *группа пользователей, которые **смотрели** контакты contacts_show;*
        - *группа пользователей, которые **не смотрели** контакты contacts_show;*
        
        
- Проверить статистические гипотезы:

    - ***1я Гипотеза:*** *конверсия в просмотры контактов различается у группы пользователей, которые совершают действия tips_show и tips_click и группы, которая совершает только tips_show;*
    - ***2я Гипотеза:*** *конверсия в просмотры контактов различается у группы пользователей, которые совершили advert_open и photos_show и группы, которая совершила только advert_open и не совершила photos_show.*
    
    
- По результатам исследования подготовить презентацию.

**Стек:**
- Python: pandas, matplotlib, numpy, seaborn, scipy, plotly, math

**Выводы:**
- Были найдены события, которые пользователи совершают чаще всего;
- Была найдена средняя длительность сессий пользователей;
- Была найдена относительная частота событий в разрезе двух групп пользователей: которые совершали целевое действие и которые не совершали;
- Были найдены наиболее популярные события пользователей в целевое действие;
- При проверке первой гипотезы выяснено, что конверсия в просмотры контактов у групп различается;
- При проверке второй гипотезы выяснено, что конверсия в целевое действие у двух групп одинковая.
- 
**Так как github не отображает графики plotly, то данный анализ доступен в формате HTML по [ссылке](https://leryash.github.io/graduation_project/)**

**[Ссылка](https://github.com/leryash/graduation_project/blob/main/presentation.pdf) на презентацию** 


# SQL: Анализ базы данных сервиса для чтения книг по подписке

**Цель:**

Провести анализ базы данных крупного сервиса для чтения книг по подписке для последующего формулирования ценностного предложения для нового продукта.

**Схема базы данных представлена ниже:**

![db_scheme](books_%20store_db.png)
