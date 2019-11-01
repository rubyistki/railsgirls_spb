## Потенциальные проблемы при установке на Windows (без WSL)

### Проблема с sqlite:
- указать в `Gemfile` версию гема:
```
gem 'sqlite3', '1.3.13'
```
- `bundle install`

### `Rails ExecJS::ProgramError`:
- указать в `Gemfile` версию гема:
```
gem 'coffee-script-source', '1.8.0'
```
- `bundle install`
