---
layout: post
title:  "Typescript Crash Course!"
date:   2022-05-04 15:40:15 +0100
categories: typescript
---
Learn typescript in (nearly) a tweet

`: thing` means “...is something with the shape of thing”
`: (argument: thing) => anotherThing` means "...is a function that returns anotherThing and takes an argument with the shape of thing"

So can you define a shape of a thing?

```ts
interface thing {
prop1: string
prop2: string
}
```

And can you type a function?

```ts
const method:
() => string = 
() => {
  return '';
};
```

The rest of typescript is about being more accurate and more reusable with how you define your types.
