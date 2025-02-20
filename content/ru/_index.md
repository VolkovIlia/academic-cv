---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Резюме
        url: uploads/resume.ru.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "11"
          description: |
            Статьи
        - statistic: "170+"
          description: |
            Цитирования
        - statistic: "5"
          description: |
            Индекс Хирша
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: '📚Научные интересы и исследования'
      subtitle: ''
      text: |-
        Занимаюсь разработкой и оптимизацией инновационных наноматериалов и гетерогенных катализаторов для решения актуальных задач в области экологии и энергетики. Мои проекты ориентированы на повышение эффективности реакций окисления и гидрирования, а также на паровой риформинг метанола, превращение CO₂ в востребованные химические продукты и получение чистой энергии из водорода.

        ### 1. Высокоэффективные катализаторы для промышленной экологии
        - Создаю биметаллические наночастицы (FePt, NiCu, Ag/Au) и покрытия на основе гексагонального нитрида бора (h-BN). Это помогает снижать температуру начала реакции и повышать селективность в таких процессах, как CO-окисление и гидрирование CO₂.
        - В рамках сотрудничества с научно-исследовательскими институтами участвую в разработке катализаторов для более рациональной утилизации парниковых газов.

        ### 2. Водородные технологии и чистая энергия
        - Исследую материалы и разрабатываю методики, позволяющие преобразовывать водород или природный газ в электричество. [Проект](https://strana-rosatom.ru/2023/11/16/giredmet-razrabotaet-tehnologiju-p/) Твердооксидных топливных элементов реализуемый в АО «Гиредмет» отражает потенциал таких систем для промышленности и домашних хозяйств.  
        - Оцениваю перспективы каталитического риформинга метанола и смешанных систем «водород + паровой риформинг», что важно для низкоуглеродной энергетики и выполнения ESG-требований.

        ### 3. Фотокатализ и очистка окружающей среды
        - Использую оксидные и бор-нитридные наноматериалы для фотодеградации органических загрязнений и глубокого окисления токсичных выбросов.
        - Особый интерес — к материалам с **внедрённым кислородом (BNOx)**, повышающим светопоглощение и каталитическую активность в УФ- и видимой областях.

        ### 4. Синтез новых композиционных материалов
        - Применяю мокрую химию, полииольные методики и искровое плазменное спекание (SPS) для формирования наноструктурированных композиций на основе Cu, Fe, Ni, Mo, W и других металлов.
        - Уделяю внимание межфазным взаимодействиям и приросту свободной энергии поверхности, за счёт чего удаётся стабилизировать наночастицы и продлить ресурс катализаторов.

        ### 5. Результаты и перспективы
        - Полученные катализаторы демонстрируют уменьшение энергозатрат в реакциях окисления CO на 30–40% и повышенную конверсию CO₂.
        - Новые наноматериалы на базе h-BN исследуются для создания УФ-фотодетекторов и фотокаталитических систем, что открывает перспективы в мониторинге окружающей среды и «зелёной» химии.
        - Технологии прямого получения электричества из водорода помогают заложить основу для чистой энергетики будущего.

        ## Зачем это бизнесу и науке?
        - Снижение промышленного углеродного следа: разработанные технологии помогают экономить ресурсы и соответствуют тренду ESG, повышая конкурентоспособность производства.
        - Ускорение перехода к чистой энергетике: эффективные материалы для низкотемпературного реформинга метанола и утилизации CO₂.
        - Перспективы масштабирования: ключевые подходы легко адаптируются для коммерческих установок и крупномасштабного выпуска нанокатализаторов.

        Такой комплексный подход — от лабораторного синтеза до тестирования и оптимизации — позволяет оперативно выводить на рынок высокотехнологичные и экологически безопасные решения, востребованные в автомобильной, нефтегазовой и химической отраслях. Я открыт к сотрудничеству, коммерческим проектам и совместным исследованиям, нацеленным на развитие энергосберегающих и экологически чистых технологий.

    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Поданные статьи
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: papers
    content:
      title: Опубликованные статьи
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Выступления
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Новости
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: demo # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Волков Илья. Исследователь
      text: |-
        Руководитель технологических проектов.
      button:
        text: Пишите
        url: 'mailto:ilia.volkov@outlook.com'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
