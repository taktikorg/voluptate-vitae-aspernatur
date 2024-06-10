## MonoRepo of JS Classes, Libraries, and Tools.

It holds the following packages:
- [**TypeCheck JS**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/type-check): A simple type checker for JavaScript.
- [**JS Utility**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/utility): Collection of libraries with classes and functions for JavaScript
- [**Node Utils**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/utility/nodeUtils): Collection of libraries with classes and functions for node.js
- [**js-event-bus**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/utility/src/event-bus): Simple Event Bus library built for any JavaScript application.
- [**BootsTrap Mini**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/bootstrap-mini): Built on top of Bootstrap but modified to have only the basic utilities classes and the grid system.
- [**Adaptive Js**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/adaptive): daptive.js: Enhancing Layout Adaptability Beyond CSS, Navigating the Complexities of Modern Web Development
- [**Vue Utils**](https://github.com/taktikorg/voluptate-vitae-aspernatur/tree/development/packages/vue-utils): Vue utilities for Vue.js applications. 

### All pacckages are ESM and CJS compatible.

## Installation

All packages are available on npm and via browser with jsDelivr. Check the README.md of each package for more information.
If you want to install all packages at once as a build tool, you can use the following command:
```bash
npm install knighttower
```
for browser use: see all packages on [jsDelivr](https://cdn.jsdelivr.net/npm/knighttower@9.0.6/packages/)

<br>

## Usage

available packages are:
- TypeCheck
- EventBus
- utility
- BootstrapMiniCss
- NodeUtils
- AdaptiveJs

Paths (aliases):
- TypeCheck: `knighttower/type-check`
- EventBus: `knighttower/event-bus`
- utility: `knighttower/utility`
- NodeUtils: `knighttower/utility/nodeUtils`
- BootstrapMiniCss: `knighttower/bootstrap-mini`
- AdaptiveJs: `knighttower/adaptive`

Access src or dist files:
- TypeCheck: `knighttower/type-check/dist/*`
- EventBus: `knighttower/event-bus/dist/*`
- utility: `knighttower/utility/dist/*`
- NodeUtils: `knighttower/utility/nodeUtils/*`
- BootstrapMiniCss: `knighttower/bootstrap-mini/dist/*`
- AdaptiveJs: `knighttower/adaptive/dist/*`

Import what you need from the package. like this:
```javascript
import { typeCheck } from 'knighttower/type-check';
import { EventBus } from 'knighttower/event-bus';
import { utility } from 'knighttower/utility';
import 'knighttower/bootstrap-mini';
import { NodeUtils } from 'knighttower/utility/nodeUtils';
import { AdaptiveJs } from 'knighttower/adaptive';
```

## Notes:
Some IDE wont show the src code when import in the file (peaking). You can use the 'package' routes if you want to be able to click and see the peak view for that.
- TypeCheck: `knighttower/packages/type-check`
- EventBus: `knighttower/packages/event-bus`
- utility: `knighttower/packages/utility`
- NodeUtils: `knighttower/packages/utility/nodeUtils`
- BootstrapMiniCss: `knighttower/packages/bootstrap-mini`
- AdaptiveJs: `knighttower/packages/adaptive`


