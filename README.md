<div align="center">

# 🚛 Trucker Simulator

[![Java](https://img.shields.io/badge/Java-17%2B-orange?style=flat-square&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Java Swing](https://img.shields.io/badge/GUI-Java_Swing-blue?style=flat-square&logo=java&logoColor=white)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![JLayer](https://img.shields.io/badge/Audio-JLayer_MP3-lightgrey?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Completed%2FArchived-yellow?style=flat-square)]()

*A pseudo-3D retro trucker simulator featuring procedural track generation, dynamic day/night cycles, and live online radio streaming.*  
*Псевдо-3D ретро-симулятор дальнобойщика с процедурной генерацией трассы, динамической сменой дня и ночи, а также стримингом живого радио.*

[English](#-english) • [Русский](#-русский)

</div>

---

## 🇺🇸 English

### 🏆 Backstory & Final Defense
This project was developed as my final graduation defense work for the Java program at SFedu (ЮФУ) in collaboration with **BetaAir**. While it didn't secure first place, it stands as a solid, fully working pseudo-3D graphics engine built entirely from scratch using Java Swing and mathematical projection algorithms without heavy third-party game engines.

### 🎮 Core Features & Architecture
- **Pseudo-3D Graphics Engine:** Custom line-based rendering algorithm (`Line.project`) that calculates scaling, perspective, road curvature, and elevation changes (hills via sine waves) on the fly.
- **Procedural Track Generation:** Generates infinite winding roads with randomized turns and elevation profiles.
- **Live Streaming Audio:** Integrated JLayer MP3 decoder to stream live internet radio (`Dorozhnoye Radio`) directly inside the simulator while driving.
- **Dynamic Environment:** Real-time day and night visual state switching affecting landscape color palettes and background imagery.
- **Keyboard Controls:** Responsive input handling via Swing's `InputMap`/`ActionMap` for smooth steering and acceleration/braking adjustments.

---

## 🇷🇺 Русский

### 🏆 История создания и защита
Этот проект разрабатывался как финальная дипломная работа для защиты по программе Java в ЮФУ перед представителями компании **BetaAir**. К сожалению, первое место занять не удалось, но проект доведён до полностью рабочего состояния и представляет собой полноценный графический движок в псевдо-3D, написанный на чистом Java Swing без использования сторонних игровых фреймворков.

### 🎮 Архитектура и особенности
- **Псевдо-3D графический движок:** Собственный алгоритм проекции линий (`Line.project`), который в реальном времени рассчитывает перспективу, ширину дороги, кривизну поворотов и перепады высот (холмы на базе синусоид).
- **Процедурная генерация трассы:** Динамическое создание дорожных сегментов с рандомизированными поворотами влево/вправо и холмами.
- **Живое интернет-радио:** Интеграция аудиобиблиотеки JLayer для потокового воспроизведения интернет-радио («Дорожное радио») прямо во время поездки.
- **Динамическая среда:** Автоматическое переключение между дневным и ночным режимами с изменением цветовой палитры ландшафта и фоновых текстур.
- **Управление:** Отзывчевое управление через `InputMap` и `ActionMap` для плавного маневрирования и контроля скорости.

---

## ⚙️ Quick Start / Быстрый старт

1. Clone the repository / Клонируйте репозиторий:
   ```bash
   git clone [https://github.com/its-shuyumi/trucker-simulator.git](https://github.com/its-shuyumi/trucker-simulator.git)
