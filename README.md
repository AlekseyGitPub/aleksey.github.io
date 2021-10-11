# Отчет о лабораторных работах
# Студент группы ИДБ-18-07 Заливалов А.Ю.
# Лабораторная :one:

###### Предложение: Даёт оценку

![RAMUS](lab1/01_A0.png)

Предложение: Пользователь даёт оценку образовательной услуги с помощью теста и опроса

###### Диаграмма классов

![PLANTUML_1](lab1/RP11IiD068NNdLFyTANW8MgzW3lNGpBOq6b6Pb9SYD0ae1j119UYLuXAgIZ6Axp_HhuG5owwol-__tllXPcboiPglV8cBOlomaQxaipRbEJAJEOsMvx7i2xpa-13bBD5KJapEOunN8xAt1CX66Bkud_fsemfKxoWnvVUOSVl6pfji1tsgTWafsmHFED7D-YrFfBXghKs1ez47xGHwZTq.png)

###### Диаграмма прецедентов

![PLANTUML_2](lab1/fP4nIyD068RdtgyuCkbGCBj8K-T0DkSZETlGD2Tt5noiO2Cu2Q8uAxYuba9HMXh_mdV_oBTS6x9t2FVc-Tvxk4i6nWfjgsd1p2GlRuGMKovIgpI_OxsXI2SZhQeokrG5qDKujvBr8gtLhIV30XKKbSwaxgBxZgyoCXL67cqivBNbLd6TZyQMPxcMgSrLoVnvapCk30_ecr.png)

# Лабораторная :two:

## IDEF0 diagram
###### Контекстная:
![RAMUS_2_1](lab2/01_A0.png)

## На диаграмме изображен процесс создания анкеты-опроса для студентов
###### Дочерняя диаграмма:
![RAMUS_2_2](lab2/02_A0.png)

**A1 - Управлять**
Администрация учреждения получает на вход повод (событие, время (конец учебного года)), а также резульаты продыдущих анкет, пройденные студентами, и составляют на их основе перечень необходимых вопросов, которые должны будут присутстовать в опросе.

**А2 - Составлять**
Менеджер системы получает план выполнения проекта в виде инструкций и информационную систему, через которую проходит анкетирование, а на вход - ресурсы

**А3 - Пройти**
Студенты, которые согласились пройти анкетирование, получают возможность ответь на вопросы в анкете

## DFD-диаграмма (блок:Управлять):
![RAMUS_2_3](lab2/03_A1.png)

## Usecase diagram
![PLANTUML_2](lab2/fL4zIyD069vxl-8bamu5Vu18M-T2DkSZETlGD2UNAmvMQ5Lq4UheAWwkHOm4Q-9VUEyV-SHhItQ796-UZoTFtklbLXexcwOYdoJPXJHoIZAosj2Lw0naD1aPFSlYKvq2EXidLebEtnXzwP512Wc4siJAjA7hLjuiLv7CrRyJKtLkoMeooMXiAKwCYcoYC-7xXaSaSmhuZGlUSCtlU7u5.png)

# Лабораторная 3

## DFD-диаграмма (блок:Составлять):
![RAMUS_3_1](lab3/04_A2.png)

## Диаграмма последовательности
![PLANTUML_3_1](lab3/VL91JiD03BplAwpUym4EgBm4BII7Ig69aWqIjpOSwG4g92u8lh113Qee2L_m_eYnrT2YI3rircjxPknHfgMpXQjkKcElNLRGX5-vvGvdmv_SXWM59M_3CjH8VOU72TcIgZ8fp5LMpMDRt06oHgs9-2SiUCixxe441-9MsssUcsJkPavwd_ZvZFWHvI_Gr-or9RRE_klvorwagJ4YID6v.png)

**Менеджер системы выполняет составление анкеты через веб-приложение.**

[Код PLANTUML](lab3/UML.txt)


## ER-диаграмма
![PLANTUML_3_2](lab3/JL2xJiCm59thhx0w8lKF64hBmiW2iqaCjUh4rRKZ1a1gosCfKYKM-8nGjI9KVVp2zHznKpSXYwrxxZd7vxXhdG2N9PhPeKf70aJ28osivG-irHFHy0vCbiPzemtmwu5oahNE0CnzG7gQA4Gq44jeGa-C1Pk-IHqOVP7U6YuiR-CNRlqBxlmODvZxDonmXrl2PlZBSK-BAG7hTgK_5qu4.png)

Вопрос является записью Базы данных, которая относится к Информационным потокам, и состоит из: Инструкций, вариантов ответа, время и даты.

[Код PLANTUML ER-диаграммы](lab3/UML2.txt)

# Лабораторная 4
# Лабораторная 5
# Лабораторная 6
