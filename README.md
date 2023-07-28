# Tesla Custom Card for Home Assistant

A big THANKS to [Thierry.P](https://forum.hacf.fr/t/lintegration-tesla-et-automatisation/7572/95) that initiated a big part of this amazing work !

<!-- <a href="https://ibb.co/PWbWfj3"><img src="https://i.ibb.co/PWbWfj3/Capture-d-cran-2023-07-28-122129.png" alt="Capture-d-cran-2023-07-28-122129" border="0"></a> -->

<a href="https://ibb.co/61hX1ss"><img src="https://i.ibb.co/b2hb2dd/Capture-d-cran-2023-07-28-132349.png" alt="Capture-d-cran-2023-07-28-132349" border="0"></a>

- Install https://github.com/custom-cards/bar-card with HACS
- Replace all the <TESLA_NAME> occurencies by the name of YOUR car.
- Add the content of scene.yaml in /config/scenes.yaml (create it if is not exist)
- Add the content of sensors.yaml in /config/sensors.yaml (create it if is not exist)
- Create a card in a dashboard with the content of tesla_card.yaml

## Configuration

There is no real configuration, just replace the <TESLA_NAME> by the name of your car. Don't hesitate ton make a pull request if you have any improvement or want to add new colors or models.

## Features

- Open/Close Trunk with a short press
- Open/Close Frunk with a long press
- Open/Close Charge Port with a short press

### To Do

- Open/Close Windows
- Lock/Unlock
- Heated steering wheel
- Temperature control
