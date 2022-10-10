# ВИРТУАЛЬНАЯ И ДОПОЛНЕННАЯ РЕАЛЬНОСТЬ 
# Программные пакеты для работы с устройствами дополненной и виртуальной реальности. Возможности Unity XR в примерах.
Отчет по лабораторной работе #2 выполнил(а):
- Шкатова Ангелина Валерьевна
- РИ-300017

Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 100 |
| Задание 2 | * | 100 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Задание 2.
- Выводы.
- ✨Magic ✨

## Цель работы
Изучить работу пакета Unity XR, настройку VR оборудования, запуск VR проекта через настроенное оборудование.

## Задание 1
### В разделе «ход работы» пошагово выполнить каждый пункт с описанием и примера реализации задач по теме лабораторной работы.

Ход работы:
1. Создайте новый Unity проект из шаблона 3D-Core;

![image](https://user-images.githubusercontent.com/79083395/193100721-0f680c48-76e0-41b6-b118-caa78e90041f.png)

2. Откройте вкладку Edit -> Project settings;

![image](https://user-images.githubusercontent.com/79083395/193100787-62d92515-c490-4b1e-9b93-f3e696358c57.png)

3. Установите XR Plugin Management;

![image](https://user-images.githubusercontent.com/79083395/193136363-708d47cd-83a9-4262-a0f9-c52993ac0414.png)

4. Настройте XR Plugin Management на работу через SDK OpenXR;

![image](https://user-images.githubusercontent.com/79083395/193137182-98a7f8d5-3867-4cf8-8acc-8673088b3e44.png)

5. Настройте режим рендера VR на каждый глаз;

![image](https://user-images.githubusercontent.com/79083395/193137254-12e8feb5-9b49-4eb2-a706-3e7b7443d44d.png)

6. Добавить поддержку контроллеров вашего оборудования;

![image](https://user-images.githubusercontent.com/79083395/193137402-c59f004f-cb75-4584-9ea6-6790f02788e2.png)

7. Через вкладку Windows -> Pacage Manager добавьте и установите пакет com.unity.xr.interaction.toolkit;

![image](https://user-images.githubusercontent.com/79083395/193138275-c0c5ed4c-b508-49c4-a6fb-006ed90ab849.png)

8. Импортируйте Starter Assets из установленного пакета;

![image](https://user-images.githubusercontent.com/79083395/193138426-b552e6f4-6c90-468d-8ecf-06a9e0ba11fd.png)

9. Настройте Input system на основе импортированного Starter Assets;

![image](https://user-images.githubusercontent.com/79083395/193138725-f4efa008-9e32-4038-a3a7-b309c5a1e00f.png)

10. Скачайте и установите Steam и Steam VR;
![image](https://user-images.githubusercontent.com/79083395/193141066-853df252-8732-4f8f-9af2-6601178a3db5.png)

11. Настройте и подключите к PC ваше VR оборудование;

30.09.2022 студенты
- Дмитриев Виталий,
- Рзаева Арзу,
- Шкатова Ангелина

проводили исследования вместе в лабораторной VR ИРИТ-РТФ, Р-306.

<img width="571" alt="1" src="https://user-images.githubusercontent.com/79083395/194868799-a290e6b6-4e9a-4e60-99b2-6cb879129d99.png">

<img width="571" alt="2" src="https://user-images.githubusercontent.com/79083395/194868829-7325221b-a8fc-4752-8397-b69f9d1f3364.PNG">

<img width="570" alt="3" src="https://user-images.githubusercontent.com/79083395/194868835-cc085704-a5c6-4c90-8b26-63889a6d4119.PNG">

<img width="570" alt="4" src="https://user-images.githubusercontent.com/79083395/194868844-0402a337-2f6d-462c-864c-f712a1543fe0.PNG">

<img width="567" alt="5" src="https://user-images.githubusercontent.com/79083395/194868853-4b949675-e8f1-4816-b2c0-1679828531e9.PNG">

12. Вернитесь в Unity и настройте запуск проекта через SteamVR;
<img width="628" alt="6" src="https://user-images.githubusercontent.com/79083395/194868893-5394d835-d58e-4399-b4bc-39c98bd600a9.PNG">

13. Добавьте объект Plane;
<img width="960" alt="7" src="https://user-images.githubusercontent.com/79083395/194868921-a9f574d4-6eff-4a38-988a-64851f3f500f.PNG">

14. Добавьте на сцену объект XR-Orig (Action Base);
<img width="960" alt="8" src="https://user-images.githubusercontent.com/79083395/194868936-5e151b9f-75d9-4679-830c-ce1855f8ef3e.PNG">

15. На объект XR Interaction Manager создайте компонент Input Action Manager;
<img width="960" alt="9" src="https://user-images.githubusercontent.com/79083395/194868969-0e3118c5-1fe0-4384-bf80-2980d3c31d0e.PNG">

16. Добавьте в Input Action Manager настроенный Input System;
<img width="960" alt="10" src="https://user-images.githubusercontent.com/79083395/194869017-019092de-0df0-4a0e-ae27-89a5b58a18e3.PNG">

17. Запустите проект и убедитесь, что он воспроизводится на VR оборудовании.
<img width="960" alt="11" src="https://user-images.githubusercontent.com/79083395/194869038-b901d22b-343d-4223-b9e2-8ce71c560e7f.PNG">

## Задание 2
### Ответьте на контрольные вопросы:
- Что значит X в аббревиатуре XR ?
В мире существует VR, AR, MR, поэтому в данном случае x подразумевает, что за место данной переменной подставляется любая буква этих понятий.

- Где VR - виртуальная реальность,
- AR - дополненная реальность,
- MR - смешанная реальность.

- Какие SDK поддерживает XR Plugin Management по Default?
ARCore
Oculus
OpenXR
Unity Mock HMD

## Выводы
В данной лабороторной работе мы изучили настройку Unity, XR plug-in для работы с VR/AR.

**BigDigital Team: Denisov | Fadeev | Panov**
