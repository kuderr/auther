TODO:
- upper case method, rstrip "/" for url and path (ez)
- tests (testify, integration tests)
- formaters, linters [https://github.com/golangci/awesome-go-linters]
- Поиск по роут паттерну (regex :( )
- settings like in pydantic. try read .env –> ignore fail, read from host env, search for config keys (search, or create this feature for GO community)
- auther 2.0
  - remove db, fill auth info on startup from auth-api. 
  - listen for changes in auth info from auth-api. 
  - decode jwt with public key (hz, interesting)