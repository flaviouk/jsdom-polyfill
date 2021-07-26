# jsdom-polyfill

## Getting Started

```bash
yarn add jsdom-polyfill
```

```json
"jest": {
  "testEnvironment": "jsdom",
  "setupFiles": ["jsdom-polyfill"]
}
```

## Why

Because jsdom doesn't support contenteditable, it makes it impossible to test editors like Remirror/Tiptap.

The code for this library was mostly extracted from [jest-remirror](https://github.com/remirror/remirror/tree/main/packages/jest-remirror), removing the specific remirror apis.
