# Полезные команды для работы с [Node.js](https://nodejs.org)

Показывает список всех доступных команд Node.js:

      node -h

Показывает установленную версию Node.js:

      node -v

Показывает список всех доступных команд пакетного менеджера:
      
      npm -h

Показывает установленную версию npm:

      npm -v

Позволяет обновить версию npm:

      npm update npm -g

Показывает список установленных пакетов:

      npm list --depth=0

Покажет список установленных пакетов, которые требуют обновления:

      npm outdated --depth=0

Позволяет установить любой пакет по его имени:

      npm install package

Укороченная альтернатива предыдущей команды:
      
      npm i package

Позволяет установить любой пакет по его имени глобально на весь компьютер:

      npm install package -g
      
Установить конкретную версию пакета:

      npm install package@1.0.1

Удаляет установленный пакет по имени:

      npm uninstall package

Покажет версию установленного пакета:

      npm list package

Покажет последнюю версию пакета, которая существует:

      npm view package version

## [NVM for Windows](https://github.com/coreybutler/nvm-windows) или [Node Version Manager](https://github.com/nvm-sh/nvm#installing-and-updating)

Установить указаную версию Node.js:

      nvm install 5.0

Переключаемся на указаную версию Node.js:

      nvm use 5.0
