# render: replaces variables within a string

> simple helper to render variables into a string

`yarn add @technik-sde/render` or `npm install @technik-sde/render`


## Example

```
import render from "@technik-sde/render";

const message = render("Unknown error {{code}} when requesting article '{{articleId}}'", {
	code: "unknown-gateway-error",
	articleId: "KKejy4VnWKP7WB5wymthtX"
});
// message: "Unhandled error: unknown-gateway-error, when requesting article 'KKejy4VnWKP7WB5wymthtX'"
```
