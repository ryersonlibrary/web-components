# rl-map



<!-- Auto Generated Below -->


## Properties

| Property                | Attribute           | Description                                                 | Type                  | Default             |
| ----------------------- | ------------------- | ----------------------------------------------------------- | --------------------- | ------------------- |
| `activeElementId`       | `active-element-id` | The ID of the currently active element.                     | `number \| undefined` | `undefined`         |
| `elements` _(required)_ | --                  | An array of the elements that will be displayed on the Map. | `MapElementDataMap`   | `undefined`         |
| `mapImage`              | `map-image`         | The image displayed on the Map.                             | `string \| undefined` | `undefined`         |
| `maxScale`              | `max-scale`         | The maximum scale factor.                                   | `number`              | `DEFAULT_MAX_SCALE` |
| `minScale`              | `min-scale`         | The minimum scale factor.                                   | `number`              | `DEFAULT_MIN_SCALE` |


## Events

| Event               | Description                                                                                                     | Type                          |
| ------------------- | --------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| `elementDeselected` | An event fired when the user deselects the selected `MapElement`.                                               | `CustomEvent<any>`            |
| `elementSelected`   | An event fired when the user selects a `MapElement`. The clicked element will be passed as the event parameter. | `CustomEvent<MapElementData>` |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
