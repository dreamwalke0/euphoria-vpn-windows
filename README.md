<div align="center">

# Euphoria VPN

VPN-клиент для Windows на базе Xray-core

</div>

## Скачать

[Download Setup]([https://github.com/dreamwalke0/euphoriavpn-windows/releases/download/1.0.0/EuphoriaVPN-Setup-1.0.0.exe](https://github.com/dreamwalke0/euphoria-vpn-windows/releases/download/1.0.0/EuphoriaVPN-Setup-1.0.0.exe)

## Возможности

- TUN-режим: через VPN идут игры, Discord и любые программы, включая UDP
- Xray-core встроен в приложение
- Вход через Telegram, профиль, подписки и устройства
- Пополнение баланса: СБП, карты, Telegram Stars, криптовалюта
- Импорт подписок и конфигов: URL, Base64, JSON, QR
- Автообновление подписок
- Выбор лучшего сервера и проверка пинга
- Discord и YouTube через VPN в один клик, остальное напрямую
- Игры мимо VPN для низкого пинга
- Split Tunnel по приложениям
- Автозапуск с Windows, работа из трея
- Светлая и тёмная тема

## Поддерживаемые протоколы

`VLESS` `VMess` `Trojan` `Shadowsocks` `SOCKS` `HTTP` `Hysteria 2`

## Поддерживаемые транспорты

`Reality` `TLS` `TCP` `WebSocket` `gRPC`  
`HTTPUpgrade` `xHTTP`

## Маршрутизация

| Режим | Описание |
|------|----------|
| 🌐 Всё через VPN | Весь трафик компьютера через VPN |
| 🇷🇺 Умный РФ | Российские сайты напрямую, заблокированные через VPN |
| 💬 Discord и YouTube | Только эти сервисы через VPN, остальное напрямую |
| 🎮 Игры напрямую | Steam, Epic Games, Riot, Battle.net, EA, Ubisoft, FACEIT и другие |
| 📂 Приложения | Свой список программ через VPN или мимо него |

## Требования

- Windows 10 или 11
- Архитектура: x64
- Права администратора один раз, для TUN-режима

## Технологии

- Go
- Wails
- React
- TypeScript
- Xray-core
- Wintun
