# Потенциальные проблемы при установке на Windows (без WSL)

1) Проблема с sqlite:
- указать в `Gemfile` версию гема:
```
gem 'sqlite3', '1.3.13'
```
- `bundle install`

2) `Rails ExecJS::ProgramError`:
- указать в `Gemfile` версию гема:
```
gem 'coffee-script-source', '1.8.0'
```
- `bundle install`
