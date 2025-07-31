# Инструкция по установке и работе с проектом

Этот документ содержит инструкции по настройке, установке зависимостей и использованию скриптов для проекта
`front-end-entrance-exam`.

## Предварительные требования

Для работы с проектом на вашем компьютере должны быть установлены:

- **[Node.js](https://nodejs.org/)**: Рекомендуется версия 18.12 или выше.
- **[pnpm](https://pnpm.io/)**: Проект использует `pnpm` в качестве менеджера пакетов.

Если `pnpm` не установлен, вы можете установить его глобально с помощью `npm` (который поставляется с Node.js):

```bash
  npm install -g pnpm
```

Установите зависимости

```bash
    pnpm install
```
Все скрипты 
``` 
"scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview",
    "lint:fix": "eslint . --fix",
    "format": "prettier --write .",
    "check-format": "prettier --check .",
    "deploy": "vite build && gh-pages -d dist"
}
```


