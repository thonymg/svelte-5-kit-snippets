
This collection of vs-code snippets is designed for developers using Svelte and SvelteKit. It offers reusable code templates to accelerate development and ensure consistent coding practices.


## Snippets Documentation

### Svelte Template:

| Prefix                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `svcomp`, `sv-comp`     | Creates a Svelte component with TypeScript - Basic structure with script tag. |
| `svhead`, `sv-head`     | Adds a svelte:head tag to manage HTML head content (meta tags, title, etc.). |
| `svfe`, `sv-for-each`   | Creates an #each loop to iterate over an array with a unique key per item.  |
| `svfee`, `sv-for-each-else` | #each loop with else block to handle empty array case.                      |
| `svif`, `sv-if`         | Simple #if conditional block for conditional rendering.                     |
| `svife`, `sv-if-else`   | #if conditional structure with else block for alternative handling.         |
| `svifeif`, `sv-if-else-if` | Complete conditional structure with #if, else if for multiple conditions.   |
| `svawait`, `sv-await`   | Asynchronous handling with #await to display different states (loading and result). |
| `svawait-short`, `sv-await-direct` | Simplified #await version that only displays the final result.            |
| `svawaittc`, `sv-await-then-catch` | Complete asynchronous handling with #await, then and catch for error management. |
| `svkey`, `sv-key`       | #key block to force component re-render when a value changes.               |
| `svon`, `sv-on-event`   | Event handler on:event with custom handler function.                        |
| `svonf`, `sv-on-event-forward` | Event forwarding to parent component.                                    |
| `svonmod`, `sv-on-event-modifiers` | Event handler with modifiers (preventDefault, stopPropagation, etc.). |
| `svoninline`, `sv-on-event-inline` | Inline event handler for simple actions directly in the template.     |
| `svb`, `sv-bind-value`  | Simple two-way binding of a property (bind:property).                       |
| `svbp`, `sv-bind-property` | Complete two-way binding between a property and a variable.                  |
| `svbf`, `sv-bind-function` | Two-way binding with custom getter/setter functions.                        |
| `svbb`, `sv-bind-block-level` | Binding of DOM element dimensions (width, height, etc.).                  |
| `svbg`, `sv-bind-input-group` | Group binding for radio and checkbox inputs sharing the same value.       |
| `svbthis`, `sv-bind-this` | Direct reference to DOM element with bind:this.                             |
| `svcl`, `sv-class`      | Conditional CSS class addition based on an expression.                      |
| `svcl-short`, `sv-class-short` | Short syntax for conditional class when name matches variable.           |
| `svuse`, `sv-use`       | Use of a Svelte action to directly manipulate a DOM element.                |
| `svusep`, `sv-use-params` | Svelte action with parameters for custom configuration.                      |
| `svtrans`, `sv-transition` | Simple transition animation (in, out, or both).                             |
| `svtransp`, `sv-transition-params` | Transition animation with custom parameters.                          |
| `svtransev`, `sv-transition-events` | Transition events handling (intro/outro start/end).                  |
| `svtransl`, `sv-transition-local` | Local transition that only affects the targeted element.               |
| `svtransa`, `sv-transition-all` | Complete transition configuration with all possible parameters.         |
| `svdebug`, `sv-debug`   | Debug point to inspect variables in the console.                            |
| `svrchild`, `sv-render-children` | Optional rendering of child content with nullability handling.          |
| `svrsnip`, `sv-render-snippet` | Definition and rendering of a reusable snippet with parameters.          |
| `svsnip`, `sv-snippet`  | Definition of a reusable snippet with parameters.                           |


### Svelte Kit:

| Prefix                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `skp`, `sk-page`        | Creates a SvelteKit page component.                                         |
| `skpl`, `sk-page-load`  | Defines a load function for fetching data in a SvelteKit page.              |
| `skpsl`, `sk-page-server-load` | Defines a server-side load function for a SvelteKit page.                  |
| `skll`, `sk-layout-load`| Defines a load function for fetching data in a SvelteKit layout.            |
| `sklsl`, `sk-layout-server-load` | Defines a server-side load function for a SvelteKit layout.              |
| `ska`, `sk-page-actions`| Defines actions for handling form submissions in a SvelteKit page.          |
| `skhh`, `sk-hooks-handle` | Customizes the request handling process in SvelteKit.                        |
| `skhf`, `sk-hooks-handle-fetch` | Customizes the fetch handling process in SvelteKit.                       |
| `skhe`, `sk-hooks-handle-error` | Handles errors that occur during request processing in SvelteKit.         |
| `skrg`, `sk-request-get` | Handles GET requests in SvelteKit.                                           |
| `skrp`, `sk-request-post` | Handles POST requests in SvelteKit.                                          |
| `skrput`, `sk-request-put` | Handles PUT requests in SvelteKit.                                           |
| `skrd`, `sk-request-delete` | Handles DELETE requests in SvelteKit.                                        |

### Svelte runes:

| Prefix                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `srs`, `sr-state`       | Svelte Runes State - Manages reactive state variables.                      |
| `srsraw`, `sr-state-raw`| Svelte: Runes State raw - Directly manipulates raw state.                   |
| `srd`, `sr-derived`     | Svelte: Runes Derived - Creates a value derived from reactive states.       |
| `srdby`, `sr-derived-by`| Svelte: Runes Derived by - Derives a value using a custom function.         |
| `sre`, `sr-effect`      | Svelte: Runes Effect - Runs a function on state changes.                    |
| `srep`, `sr-effect-pre` | Svelte: Runes Effect - Runs a function before DOM updates.                  |
| `srep`, `sr-effect-root`| Svelte: Runes Effect creates a non-tracked scope - Creates an effect without auto-cleanup. |
| `srp`, `sr-props`       | Svelte: Runes Props - Handles component properties with renaming.           |
| `srpid`, `sr-props-id`  | Svelte: Runes props id - Gets the identifier of a prop.                     |
| `srpbind`, `sr-props-bindable` | Svelte: Runes props bindable - Manages bindable reactive properties.         |

### Svelte store:

| Prefix                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `ssw`, `ss-writable`    | Creates a writable store with subscription, set and update methods for reactive state management. |
| `ssr`, `ss-readable`    | Creates a readable store with start/stop functionality for read-only reactive values. |
| `sscget`, `ss-context-get` | Retrieves a value from component context using getContext - useful for component communication. |
| `sscset`, `ss-context-set` | Sets a value in component context using setContext - for passing data down component tree. |

### Svelte superform & formsnap & zod:

| Prefix                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `sfla`, `ss-load-actions` | Creates SvelteKit load function and form actions with SuperForms validation using Zod schema. |
| `sfv`, `ss-validation`  | Creates a Zod schema for form validation with SuperForms, including TypeScript type. |
| `sft`, `ss-template`    | Sets up SuperForms client-side validation and form handling with TypeScript support. |

-------------------------------------------

## ❤️ Contributors

This project was initiated and is maintained by [ThonyMg](https://github.com/ThonyMg). I am available for freelance work on Svelte and VueJs projects. Feel free to reach out through my [Linkedin profile](https://www.linkedin.com/in/thonymg/) for collaboration opportunities.

## ⚖️ License

This project is licensed under the MIT License. For more details, see the [LICENSE](https://github.com/thonymg/svelte-5-kit-snippets/blob/master/license) file.

