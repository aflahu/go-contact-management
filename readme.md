# Contact Management System

## Prerequisite
- install go
- install docker

## Setup
- `docker compose up` for starting database
- `go mod tidy`
- copy `.env.example` to `.env`

## Running
- `go run main.go`

## Features

- [x] Database Migration
- [x] Create Data
- [x] Read All Data
- [x] Find One Data By ID
- [x] Update Data
- [x] Delete One Data By ID
- [x] Delete Multiple Data By IDs
- [x] Sort & Paginate Data
- [x] Search Data

## API list

```bash
[GIN-debug] POST   /create                   --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func1 (3 handlers)
[GIN-debug] GET    /                         --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func2 (3 handlers)
[GIN-debug] GET    /show/:id                 --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func3 (3 handlers)
[GIN-debug] PUT    /update/:id               --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func4 (3 handlers)
[GIN-debug] DELETE /delete/:id               --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func5 (3 handlers)
[GIN-debug] POST   /delete                   --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func6 (3 handlers)
[GIN-debug] GET    /pagination               --> github.com/aflahu/go-contact-management/configs.SetupRoutes.func7 (3 handlers)
```
