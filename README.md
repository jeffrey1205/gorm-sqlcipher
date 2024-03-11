# GORM Sqlite Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  sqlcipher "github.com/jeffrey1205/gorm-sqlcipher"
  "gorm.io/gorm"
)

// https://github.com/jeffrey1205/go-sqlcipher
db, err := gorm.Open(sqlcipher.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
