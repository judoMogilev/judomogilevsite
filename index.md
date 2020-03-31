---
title: Home
sidebar:
  entries:
  - title: Главная
    url: "#intro"
    is_primary: true
  - title: О нас
    url: "#one"
    is_primary: false
  - title: Общая информация
    url: "#two"
    is_primary: false
  - title: Контакты
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Школа Дзюдо
  subtitle: "#### Дисциплина и самооборона.\n\nГибкость и равновесие   \nСамосознание,
    концентрация и внимательность."
  section_id: intro
  background_style: style2
  actions:
  - label: О нас
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: intro.html
- type: spotlights
  template: spotlights
  title: О нашей школе
  section_id: one
  background_style: style2
  component: spotlights.html
- type: features
  template: features
  title: Что мы делаем
  subtitle: |-
    Мы проводим набор детей с 4-х лет. В тренировках используем игровой метод. Напольное покрытие– татами (мягкое покрытие) на котором можно безболезненно кувыркаться, ползать и падать. Для каждого возраста у нас разработана специальная программа тренировок. Таким образом, мы обеспечиваем индивидуальный подход.

    ### **Основными целями занятий являются**
  section_id: two
  background_style: style3
  features_list:
  - title: Здоровье
    text: Сохранить и укрепить здоровье детей, способствовать их физическому развитию,
      избегая нервных и физических перегрузок
    icon: fa-heart
  - title: Поддержка
    text: Внимательно относиться к формирующемуся детскому сообществу и терпеливо
      поддерживать его.
    icon: fa-handshake-o
  - title: Культура
    text: Формировать основы культурного поведения в природе и обществе
    icon: fa-level-up
  - title: Развитие способностей
    text: Развивать у детей познавательные интересы, сенсорные и интеллектуальные
      способности
    icon: 'fa-graduation-cap '
  - title: Творчество
    text: Развивать воображение и творческое начало
    icon: fa-paint-brush
  - title: Развитие характера
    text: В процессе занятий закаляется характер, развивается способность к лучшей
      концентрации сознания, сохранение спокойствия, находясь под давлением любых
      обстоятельств. И конечно же физическое развитие
    icon: fa-balance-scale
  actions:
  - label: Читать далее
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: features.html
- type: contact
  template: contact
  title: Интересно, правда?
  text: |-
    #### Если у Вас остались вопросы, или Вы хотите уточнить расписание занятий и наличие вакансий в группах, ответы на вопросы вы можете найти на сайте, либо связавшись с нами.

    ### Мы будем рады Вам!
  section_id: three
  background_style: style1
  contact_list:
  - title: Адрес
    text: |-
      г. Могилев,
      ул. Пионерская,
      дом 24 "А"
    url: https://yandex.by/maps/158/mogilev/house/Z0kYdQRpSUUOQFtpfXR4eH1hZg==/?ll=30.339009%2C53.899122&sll=30.330654%2C53.894548&sspn=0.493011%2C0.165675&z=17.03
  - title: Телефоны
    text: |-
      +375 (29) 632-91-62
      +375 (29) 638-64-58
    url: ''
  social:
    title: ''
    social_icons: []
  component: contact.html
layout: home
menu:
  main:
    weight: 1

---
