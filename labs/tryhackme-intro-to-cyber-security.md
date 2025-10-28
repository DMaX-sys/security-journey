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
- ## Задание: What phase of the incident response process involves providing "cyber awareness" training to employees?

- **Вопрос**: What phase of the incident response process involves providing "cyber awareness" training to employees?
- **Мой ответ**: Preparation
- **Обоснование**: Этап подготовки (Preparation) включает обучение персонала, настройку инструментов защиты и разработку политик. Cyber awareness training помогает предотвратить инциденты, вызванные человеческим фактором (например, фишинг).
- **Связь с практикой**: Как будущий SOC-аналитик, я понимаю: лучшая защита — это не только технологии, но и осведомлённые пользователи.
## 🎯 Завершение комнаты: Defensive Security Intro

Дата: 24 октября 2025  
Комната: [Defensive Security Intro](https://tryhackme.com/room/introtocybersecurity)  
Тип: Walkthrough  
Сложность: Easy  
Задачи выполнены: 5  
Баллы получены: 40  
Стрик: 2  

### Что я изучил:
- Разницу между Blue Team и Red Team
- Основные принципы защиты: CIA триада, мониторинг, политики безопасности
- Этапы Incident Response: Preparation, Detection, Containment, Eradication, Recovery, Lessons Learned
- Важность обучения сотрудников (cyber awareness training)
- Техники цифровой криминалистики: анализ памяти для fileless malware

### Вывод:
Эта комната дала мне прочный фундамент для работы в SOC. Я понял, что защита — это не только технологии, но и люди, процессы и осведомлённость. Моя цель — стать Junior SOC Analyst, и этот шаг приближает меня к ней.
## 🧠 Задание: Криптография и Linux

Дата: 28 октября 2025  
Комната: Intro to Cyber Security  
Задачи выполнены: 5 / 5  
Баллы: 40  
Прогресс: 100%

### Вопрос 1:  
- **Вопрос**: Как вы называете криптографический метод или продукт, считающийся поддельным?
- **Мой ответ**: Snake Oil
- **Обоснование**: Термин "Snake Oil" используется для обозначения бесполезных или обманчивых криптопродуктов, которые не обеспечивают реальной защиты. Часто встречается в ИБ при анализе фишинговых писем или ложных инструментов безопасности.

### Вопрос 2:  
- **Вопрос**: Как называется команда, заменяющая `нетстат` в системах Linux?
- **Мой ответ**: ss
- **Обоснование**: Команда `ss` — современная замена `netstat`, выводит информацию о сокетах и сетевых соединениях. Она быстрее и детальнее, особенно в новых версиях Linux.

### Вывод:  
Эти вопросы помогли мне понять важность критического мышления при оценке информации и знакомство с базовыми командами Linux — ключевым навыком для SOC-аналитика.
