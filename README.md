# DIY Osiloscope with Wifi

## Description

This project is used to document the development of mini osiloscope for local school practice in physics course. The final product hopefully cost under 13$.


## System overview

Target:
- Osilocsope:
  - Data capture
  - Trigger
  - 2 Channel
- Signal generation:
  - Positive and negative signal generation
  - Current control (if posible)
- Web view
- Safety
  - Current protection
  - voltage protection
- USB Power delivery

| Item            | Description                                       |
| --------------- | ------------------------------------------------- |
| STM32 Blue pill | Signal generation, accusition, and main processor |
| ESP32 Mini      | Wifi capability and online view                   |
