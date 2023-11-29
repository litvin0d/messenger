# Мессенджер на стеке: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher

### Предварительные требования

**Версия Node 14.x**

### Клонирование репозитория

```shell
git clone https://github.com/AntonioErdeljac/next13-messenger.git

```

### Установка пакетов

```shell
npm i
```

### Настройка файла .env


```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Настройка Prisma
```shell
npx prisma db push

```

### Запуск приложения

```shell
npm run dev
```
