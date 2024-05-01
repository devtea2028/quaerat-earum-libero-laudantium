[![npm](https://img.shields.io/npm/v/@devtea2028/quaerat-earum-libero-laudantium.svg)](https://www.npmjs.com/package/@devtea2028/quaerat-earum-libero-laudantium) ![downloads](https://img.shields.io/npm/dt/@devtea2028/quaerat-earum-libero-laudantium.svg) [![CI](https://github.com/devtea2028/quaerat-earum-libero-laudantium/actions/workflows/ci.yml/badge.svg)](https://github.com/devtea2028/quaerat-earum-libero-laudantium/actions)

# Make-Event-Props

A function that, given props, returns an object of event callback props optionally curried with additional arguments.

This package allows you to pass event callback props to a rendered DOM element without the risk of applying any invalid props that could cause unwanted side effects.

## tl;dr

- Install by executing `npm install @devtea2028/quaerat-earum-libero-laudantium` or `yarn add @devtea2028/quaerat-earum-libero-laudantium`.
- Import by adding `import makeEventProps from '@devtea2028/quaerat-earum-libero-laudantium'`.
- Create your event props object:
  ```ts
  const eventProps = useMemo(
    () => makeEventProps(props, (eventName) => additionalArgs),
    [additionalArgs],
  );
  ```
- Use your event props:
  ```tsx
  return <div {...eventProps} />;
  ```

## License

The MIT License.

## Author

<table>
  <tr>
    <td >
      <img src="https://avatars.githubusercontent.com/u/5426427?v=4&s=128" width="64" height="64" alt="Wojciech Maj">
    </td>
    <td>
      <a href="https://github.com/wojtekmaj">Wojciech Maj</a>
    </td>
  </tr>
</table>
