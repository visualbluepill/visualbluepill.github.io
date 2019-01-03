# Simulator

The JavaScript simulator lets you run and test most @boardname@ programs in the browser.
It simulates sensor inputs and user interactions.

##  #example

```sim
input.leftButton.onEvent(ButtonEvent.Click, () => {
});
input.rightButton.onEvent(ButtonEvent.Click, () => {
});
input.temperature(TemperatureUnit.Celsius)
input.lightLevel()
input.acceleration(Dimension.Y)
```
