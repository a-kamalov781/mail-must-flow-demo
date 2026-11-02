# Почта не спит / Mail Must Flow — демоверсия

## [▶ Играть бесплатно в браузере](https://a-kamalov781.github.io/mail-must-flow-demo/)

Игра про автоматизацию маленького почтового отделения. Сначала вы сортируете письма вручную, затем покупаете робота и задаёте ему программу на небольшом языке, похожем на Python.

- Компьютер, клавиатура и мышь или тачпад. Установка и регистрация для игры не нужны.
- Интерфейс на русском и английском: переключатель **RU / EN** находится сверху.
- Прогресс сохраняется **в конце каждой смены** в текущем браузере. Чтобы продолжить, откройте игру в том же браузере.
- Это ранняя демоверсия для обратной связи.
- Сортировка — двумя отдельными нажатиями: письмо, затем ящик с той же меткой. Перетаскивать не нужно.
- В первой смене нет штрафов за потерянные письма; каждая доставка приносит 1 монету. Штрафы за потери начинаются со второй смены.

Открыли страницу с телефона? Кнопка **«Скопировать ссылку для компьютера»** помогает открыть демо на компьютере. Она копирует только публичную ссылку; сохранение остаётся в исходном браузере. Если автоматическое копирование недоступно, игра покажет адрес для ручного копирования.

В заключительном задании филиал получает своё стартовое оборудование. Улучшения филиала можно купить отдельно. Старые сохранения корректно определяют уже купленные улучшения по фактическому оборудованию.

Если программа робота закончилась без повторяющегося цикла, смена останавливается на паузу. Ошибка указывает на робота и последнюю строку; удерживаемое письмо возвращается в свой лоток. Исправьте программу и нажмите «Запустить код» или верните рабочий код.

## Первый игровой тест: 10–15 минут

Начните первую смену, попробуйте разобраться в сортировке и добраться до первого робота. Проходить всё демо необязательно. Если вы застряли или захотели остановиться, это тоже полезное наблюдение.

После игры расскажите:

1. До какого момента вы дошли?
2. Где впервые стало непонятно, что делать?
3. Захотелось ли продолжить — и почему?

В самой игре есть кнопка **«Оставить отзыв»** под игровым полем и в итогах смены:

- **[Короткое впечатление — в комментариях DTF](https://dtf.ru/indie/5387999-pochta-ne-spit-roboty-i-avtomatizatsiya)**.
- **[Отзыв или ошибка с подробностями — форма GitHub](https://github.com/a-kamalov781/mail-must-flow-demo/issues/new?template=playtest.yml)**.

Ссылки открываются в новой вкладке. Для отправки нужен аккаунт выбранной площадки; отзывы публичные. По желанию можно скопировать версию и несколько сведений о текущем прохождении. Они не отправляются автоматически. После открытия отзыва активная смена остаётся на паузе — продолжите её кнопкой «Дальше».

В первой смене увеличение лотка открывается после первого робота, чтобы не потратить нужные для него 40 монет. Перед повтором смены игра показывает стартовый бюджет: заработок попытки сбросится, а покупки и код сохранятся. Доход разных повторов не складывается. Если купить улучшение из итогового экрана, сумма для повтора обновится сразу. Подтверждение работает и у кнопки повтора в отчёте; отмена сохраняет текущую попытку.

## English

**[Play the free browser demo](https://a-kamalov781.github.io/mail-must-flow-demo/)**

Mail Must Flow is a game about automating a small post office. Sort letters by hand, buy a robot, and program it with a small Python-like language. Play on a computer with a keyboard and a mouse or touchpad; no installation or game account is needed. The interface supports Russian and English.

Progress is saved **at the end of each shift**, locally in the current browser. Use the same browser to continue.

Opened the page on a phone? Use **Copy link for a computer** to open the demo on a computer. It copies only the public link; progress stays in the original browser. If automatic copying is unavailable, the game shows the address for manual copying.

The final branch task has its own starting equipment. Branch upgrades can be bought separately. Existing branch saves correctly recognize purchased upgrades from their actual equipment.

If a robot program ends without a repeating loop, the shift pauses. The error selects the robot and its last line; a held letter returns to its tray. Fix the program and choose Run code, or restore the working code.

Manual sorting uses two separate clicks: envelope, then the bin with the same mark. No dragging is needed. Shift 1 has no fines for lost letters; each delivery still earns 1 coin. Loss fines begin in shift 2.

For a first playtest, try 10–15 minutes. Tell us how far you got, where you first felt unsure, and whether you wanted to keep playing. Finishing the demo is optional.

Use **Leave feedback** below the game or in a shift report to open the **[DTF comments](https://dtf.ru/indie/5387999-pochta-ne-spit-roboty-i-avtomatizatsiya)** or the **[GitHub feedback form](https://github.com/a-kamalov781/mail-must-flow-demo/issues/new?template=playtest.yml)**. Links open in a new tab; posting requires an account on the chosen site, and feedback is public. English feedback is welcome. You can optionally copy the game version and current state for a bug report. These details are not sent automatically. Opening feedback pauses an active shift; use Resume when you are ready to continue.

In shift 1, the tray upgrade unlocks after your first robot, so you can save the 40 coins it needs. Before replaying, the game shows the starting budget: earnings from this attempt reset, while purchases and code are kept. Earnings from separate replays do not add up. Buying an upgrade from a shift report immediately updates its replay budget. Report replay buttons also ask for confirmation; Cancel keeps the current result.

## О сборке / Build

- Version: `v15.5.1-public-demo7`.
- The game is contained in `index.html`; no external assets or build step are required. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.
- Код создавался и редактировался с помощью ИИ. / The code was created and edited with AI assistance.
