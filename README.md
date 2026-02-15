# Laboratory Work 1 — Setup

## Lab 1 goal (Мета роботи)
Налаштувати середовище розробки для React Native через Expo та підготувати базову структуру проєкту.

## Tech stack
VS Code, React Native, Expo, TypeScript, JSX, Node.js

## Setup steps
1. Створити папку проєкту з назвою `<SURNAME>_MobileDevCource`.
2. Відкрити папку у VS Code.
3. Запустити команди:
   - `npx create-expo-app .`
   - `npx expo -v`
   - `npx expo start`

## Run instructions
- Запуск: `npx expo start`
- Зупинка: `Ctrl + C`
- Повторний запуск: `npx expo start`

## Verification commands with expected versions
- `node -v` -> `v24.12.0`
- `npm -v` -> `11.6.2`
- `npx -v` -> `11.6.2`

## How to test in Expo Go
1. Встановити Expo Go на телефон.
2. Запустити `npx expo start`.
3. Відсканувати QR-код у терміналі через Expo Go.

## How to open in web
- Натиснути `w` у терміналі Expo
- Або виконати `npx expo start --web`

## Common issue
Після встановлення нового пакета застосунок не оновився: перезапустіть Expo Go або зупиніть сервер (`Ctrl + C`) і запустіть `npx expo start` знову.
