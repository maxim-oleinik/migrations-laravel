# Release Notes

## [0.2.2 (2019-08-10)](https://github.com/maxim-oleinik/blade-migrations-laravel/compare/0.2.1...0.2.2)
#### Changed
- ServiceProvider: remove DbAdapter from provides()
- composer: add extra for Laravel Auto-Discover Package


## [0.2.1 (2019-06-09)](https://github.com/maxim-oleinik/blade-migrations-laravel/compare/0.2.0...0.2.1)
#### Added
- `migrate -t|test` - add rollback test mode (UP-DOWN-UP)
- `reload` - new command to reload selected migration (DOWN-UP)
- `rollback -l|load-file` - "-l" shortcut for "--load-file"

#### Changed
- `status` - changed color scheme (green for new/not applied migrations)
