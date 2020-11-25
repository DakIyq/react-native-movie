# React native movie

React native movie module

## Installation

```sh
npm install --save DakIyq/react-native-movie
```

or

```sh
yarn add DakIyq/react-native-movie
```

## Usage

```js
const releases = [
    {
      "id": 1,
      "category": "Science Fiction",
      "title": "Blade Runner Future 2049.",
      "image": { "uri": "https://i.imgur.com/mMbMK47.jpg" },
      "rating": 4.0,
      "description": "Lorem ipsum dolor sit amet."
    }
]

const suggestions = [
    {
      "id": 1,
      "category": "Drama",
      "title": "Shawshank Redemption.",
      "image": { "uri": "https://i.imgur.com/1rHP7BF.jpg" },
      "rating": 5.0,
      "description": "Lorem ipsum dolor sit amet."
    }
]
```

```js
import Movie from "react-native-movie";

// ...

<Movie releases={releases} suggestions={suggestions} />
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
