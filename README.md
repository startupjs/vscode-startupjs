# vscode-startupjs

[StartupJS](https://github.com/startupjs/startupjs) support for VS Code.

## Features

1. Highlight syntax inside `styl` template literal:

    ```js
    /* eslint-disable no-unreachable */
    import React from 'react'
    import { styl, observer } from 'startupjs'
    import { Div } from '@startupjs/ui'

    export default observer(function MyComponent () {
      return <Div styleName='root' />

      styl`
        .root
          width 10u
          height 10u
          background-color green
      `
    })
    ```

## Install

Inside VSCode, press `Ctrl+P`, and enter:

```
ext install vscode-startupjs
```
