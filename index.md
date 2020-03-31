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
    icon: fa-yin-yang
  - title: Развитие
    text: Развивать у детей познавательные интересы, сенсорные и интеллектуальные
      способности
    icon: fa-award
  - title: Творчество
    text: Развивать воображение и творческое начало
    icon: fa-icons
  - title: Aliquam urna dapibus
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-diamond
  actions:
  - label: Learn more
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: features.html
- type: contact
  template: contact
  title: Get in touch
  text: Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis mauris,
    eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget hendrerit bibendum,
    urna est aliquam sem, sit amet imperdiet est velit quis lorem.
  section_id: three
  background_style: style1
  contact_list:
  - title: Address
    text: |-
      12345 Somewhere Road #654
      Nashville, TN 00000-0000
      USA
    url: ''
  - title: Email
    text: user@Hyperspace.tld
    url: "#"
  - title: Phone
    text: "(000) 000-0000"
    url: ''
  social:
    title: Social
    social_icons:
    - title: Twitter
      icon: fa-twitter
      url: "#"
    - title: Facebook
      icon: fa-facebook
      url: "#"
    - title: GitHub
      icon: fa-github
      url: "#"
    - title: Instagram
      icon: fa-instagram
      url: "#"
    - title: LinkedIn
      icon: fa-linkedin
      url: "#"
  component: contact.html
layout: home
menu:
  main:
    weight: 1

---
