## DOM Manipulation

---

```
- MDN명세 [미지원버전] [반환타입]
```

```
상 -> 속
EventTarget -> Node -> Element -> HTMLElement -> HTML***Element
```

---

1. [Element.outerHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML) [-]
2. [Element.innerHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML) [-] [string]
3. [Node.innerText](https://developer.mozilla.org/ko/docs/Web/API/HTMLElement/innerText) [-]
4. [Node.textContent](https://developer.mozilla.org/ko/docs/Web/API/Node/textContent) [-]
5. [HTMLTemplateElement.content](https://developer.mozilla.org/en-US/docs/Web/API/HTMLTemplateElement/content) [IE] [object DocumentFragment]  
   The HTMLTemplateElement.content property returns a `<template>` element's template contents (a DocumentFragment).

   - cf: [Window.content](https://developer.mozilla.org/en-US/docs/Web/API/Window/content) [비표준]
   - cf: [DocumentFragment](https://developer.cdn.mozilla.net/en-US/docs/Web/API/DocumentFragment) [IE△]

---

1. [HTMLElement](https://developer.mozilla.org/ko/docs/Web/API/HTMLElement)
2. [HTMLTemplateElement](https://developer.cdn.mozilla.net/ko/docs/Web/API/HTMLTemplateElement) [IE] [object HTMLTemplateElement]  
   HTMLElement 의 프로퍼티, 메소드를 상속받습니다.
