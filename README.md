vue-weathericons
=============

VueJs component for [weathericons](https://erikflowers.github.io/weather-icons/) using CSS.

## Requirements

- [weathericons](https://www.npmjs.com/package/weathericons)

## Installation

``` sh
npm install --save npm install git@github.com:porcej/vue-weathericons.git
```

## Usage

In your component:

```vue
<script>
import VueWeatherIcon from 'vue-weathericons';

export default {
  name: 'myComponentName',
  // [...]
  components: {
    VueWeatherIcons
  }
};
</script>

<template>
  <div class="whatever">
    <p>All attributes are optional and non mutually exclusive, apart from the 'icon' of course:</p>
    <weather-icon icon="day-sunny" />
    <weather-icon icon="wind" wind="towards-NW" />
    <weather-icon icon="wind" windDeg="towards-160" />
    <weather-icon icon="tornado" flip="horizontal" />
    <weather-icon icon="alien" rotate="45" />
    <weather-icon icon="fog" fixed="true" />
  </div>
</template>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
