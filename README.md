# Opus Website Block Scheme

```mermaid

graph TD
  A[Главная страница] -->|Навигация| B[О нас]
  A -->|Навигация| C[Услуги]
  A -->|Навигация| D[Контакты]
  A -->|Навигация| E[Личный кабинет]

  B -->|Информация| F[Страница "О нас"]
  C -->|Список услуг| G[Страница "Услуги"]
  D -->|Контактная информация| H[Страница "Контакты"]
  E -->|Логин, Профиль, История операций| I[Личный кабинет]

  A -->|Футер| J[Футер]

  style A fill:#80b3ff
  style B fill:#80b3ff
  style C fill:#80b3ff
  style D fill:#80b3ff
  style E fill:#80b3ff
  style F fill:#b3d9ff
  style G fill:#b3d9ff
  style H fill:#b3d9ff
  style I fill:#b3d9ff
  style J fill:#ccf2ff

```



