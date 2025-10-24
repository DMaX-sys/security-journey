# TryHackMe: Intro to Cyber Security

Дата: 23 октября 2025  
Цель: понять разницу между наступательной и оборонительной безопасностью

## Задание: Команды ИБ
- Вопрос: Which team focuses on defensive security?
- Ответ: Blue Team
- Вывод: как SOC-аналитик, я буду работать в Blue Team — защищать систему, а не атаковать её.
- ## Задание: What would you call a team of cyber security professionals that monitors a network and its systems for malicious events?

- **Вопрос**: What would you call a team of cyber security professionals that monitors a network and its systems for malicious events?
- **Мой ответ**: Security Operations Centre (SOC)
- **Обоснование**: SOC — это центр круглосуточного мониторинга безопасности, который выявляет, анализирует и реагирует на киберугрозы. Именно в SOC работают аналитики уровня L1/L2, используя SIEM, EDR и другие инструменты.
- **Связь с моей целью**: Моя карьера начинается именно с позиции **Junior SOC Analyst** — я стремлюсь войти в такую команду и внести вклад в защиту инфраструктуры.
## Задание: An attacker deploys a piece of malicious code that does not save to the disk. What digital forensics technique would we use in this instance?

- **Вопрос**: An attacker deploys a piece of malicious code that does not save to the disk. What digital forensics technique would we use in this instance?
- **Мой ответ**: System Memory
- **Обоснование**: Такой вредонос (fileless malware) работает только в оперативной памяти и не оставляет следов на диске. Для его анализа требуется сбор и исследование дампа оперативной памяти (memory dump) с помощью инструментов вроде Volatility или Rekall.
- **Связь с практикой**: В SOC и цифровой криминалистике анализ памяти — критически важный навык при расследовании сложных инцидентов.
