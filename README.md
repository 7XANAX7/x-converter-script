<p align="center">
  <img src="https://i.imgur.com/O0yGBbD.gif" alt="animated" width="600" heigth="200"/>
</p>


# ЭТО БИБЛИОТЕКА, ОНА БУДЕТ РАБОТАТЬ ТОЛЬКО В JS. ИСПОЛЬЗУЙТЕ CLI ДЛЯ ОБЫЧНОГО ИСПОЛЬЗОВАНИЯ.

---

## Как это работает

Эта библиотека может конвертировать скрипты FiveM ESX в Qbus и Qbus в ESX.

---

### Использование

```js
const converter = require('x-fivem-script-converter');

// для преобразования скрипта qbus в esx
converter.qbustoesx('path/to/qbus/script.lua');
// ===============================


// для преобразования скрипта esx в qbus
converter.esxtoqbus('path/to/esx/script.lua');
// ===============================
```