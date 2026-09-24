# telegram-web-mcp fixtures

Static pages for end-to-end tests, served by GitHub Pages at
https://twoam-inc.github.io/telegram-web-mcp-fixtures/miniapp/

`miniapp/` is a test Telegram Mini App. Every control on it exists only to be driven by automated tests.
`login/` is the target of the fixture bot's `login_url` button; it shows which fields arrived and never prints the hash.
