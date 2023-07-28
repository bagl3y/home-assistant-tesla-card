# Tesla Custom Card for Home Assistant

## A big THANK YOU to [Thierry.P](https://forum.hacf.fr/t/lintegration-tesla-et-automatisation/7572/95) who initiated a significant part of this amazing work!

<a href="https://imgbb.com/"><img src="https://i.ibb.co/b2hb2dd/Capture-d-cran-2023-07-28-132349.png" alt="Capture-d-cran-2023-07-28-132349" border="0" /></a>

- Install https://github.com/custom-cards/bar-card with HACS.
- Replace all occurrences of `<TESLA_NAME>` with the name of YOUR car.
- Add the content of `scene.yaml` to `/config/scenes.yaml` (create it if it does not exist).
- Add the content of `sensors.yaml` to `/config/sensors.yaml` (create it if it does not exist).
- Create a card in a dashboard with the content of `tesla_card.yaml`.

## Configuration

There is no real configuration, just replace `<TESLA_NAME>` with the name of your car. Don't hesitate to make a pull request if you have any improvements or want to add new colors or models.

## Features

- Open/Close Trunk with a short press.
- Open/Close Frunk with a long press.
- Open/Close Charge Port with a short press.

### To Do

- Open/Close Windows.
- Lock/Unlock.
- Heated steering wheel.
- Temperature control.
