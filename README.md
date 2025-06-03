# GoZenko Common

Библиотека общих утилит для Go-проектов.

## Описание

Этот пакет содержит общие утилиты, которые могут быть использованы в различных Go-проектах. В настоящее время включает:

- Логирование (logger.go)
- Работа с JWT токенами (jwt.go)

## Установка

```bash
go get github.com/yourusername/gozenko_common
```

## Использование

### Логирование

```go
import "github.com/yourusername/gozenko_common"

// Пример использования логгера
logger := gozenko_common.NewLogger()
logger.Info("Информационное сообщение")
```

### JWT

```go
import "github.com/yourusername/gozenko_common"

// Пример работы с JWT токенами
token, err := gozenko_common.GenerateToken(userID)
```

## Лицензия

MIT 