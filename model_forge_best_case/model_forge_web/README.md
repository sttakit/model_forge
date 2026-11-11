# MODEL FORGE — animated HTML/CSS prototype

A multi-page responsive frontend prototype that continues the supplied MODEL FORGE visual language:
near-black green surfaces, low-contrast orbital background, thin green borders, restrained lime actions,
compact technical typography, and subtle motion.

## Run
Open `index.html` in a modern browser. No build step required.

## Pages
- Home
- Projects (search, status filter, sorting)
- Data (drag/drop and file chooser demo, dataset selection and preview)
- New Run (task form and configurable options)
- Runs (search and status filter)
- Live Monitoring
- Results (demo metrics and SVG comparison chart)

## Notes
- `assets/orbital-reference.png` is the supplied atmospheric visual reference used as a background.
- The data and model metrics are illustrative demo content.
- File uploads stay in the browser session; no file is sent to a server.
- Model training, real notifications, artifact downloads, and backend persistence are not connected.
- Fonts load from Google Fonts when online; system fallbacks are included.
- Respects `prefers-reduced-motion`.


## Обновлённый мониторинг агента

На странице мониторинга есть 7 последовательных этапов, статус каждого этапа, текущая причина выбора следующего действия, история экспериментов и лента логов. В демонстрационном режиме прогресс переключается автоматически примерно каждые несколько секунд. Значения и результаты демонстрационные; для реального обучения необходим backend. Кнопка остановки останавливает только демо-симуляцию.
