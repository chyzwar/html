

Tagged template literals for html.


```js
import html from "@hyper/html"

function view(items){
  return html`<ul>
    ${items.map(function (item) {
      return yo`<li>${item}</li>`
    })}
    </ul>`
}


```