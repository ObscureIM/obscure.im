---
layout: уведомления
title: NavCoin 4.2.1 - 32Bit NTP Sync Hotfix
author: Craig MacGregor
date: '2018-06-11T12:15:16+12:00'
feature_image: /images/uploads/2018-06-06.jpg
notice_categories:
  - Патч NavPi
---
Проблема, мешающая пользователям NavPi успешно обновлять версию до 4.2.0 исправлена в версии 4.2.1. Если вы используете NavPi и хотите поддержать софтфорк наколения в Фонд Сообщества, убедитесь, что вы обновляете NavPi до последней версии и продолжаете осуществлять стекинг с помощью новой версии.
<!--more-->

## Примечания к релизу

- Кошелек при запуске будет пытаться синхронизировать часы каждые 30 секунд до тех пор, пока он в этом не преуспеет, вместо того, чтобы проверить один раз и выйти в случае неудачной попытки.
- Принуждает использование 32-битного типа данных для буфера при чтении из сокета NTP-сервера, устраняя некоторые проблемы совместимости с 32-битными системами, такими как Raspberry Pi.
- Уменьшает время ожидания NTP-соединения до 5 секунд..

https://github.com/NAVCoin/navcoin-core/releases/tag/4.2.1

Ваш NavPi должен автоматически обновиться до последней версии в течение 24 часов, после чего вам необходимо войти в систему и перезагрузить устройство. Или, если вы хотите самостоятельно обновить до последней версии, изучите статью:

https://info.navcoin.org/knowledge-base/how-to-update-the-navpi

Если у вас возникнут проблемы с обновлением, присоединяйтесь к сообществу в discord для получения дальнейшей помощи.

https://discord.gg/y4Vu9jw
