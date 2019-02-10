# Experiment Labs at DCE on 6 February 2019

| Experiment | By | Summery |
| ------ | ------ | ------ | 
| [Nova event-sourcing actions](#nova-event-sourcing-actions) | [Mohammed Rajab](https://github.com/mohrajab) | TBD |
| [Stress and Perfomance testing](#stress-and-perfomance-testing) | [Akram Mushtaha](https://github.com/Akram-oo7) | TBD |
| [.Net Core DDD & CQRS](#net-core-ddd--cqr) | [Akmal Aldahdouh](https://github.com/topmax),  [Mohammed Shurrab](https://github.com/devmsh) | TBD |
| [Package docs as Github pages](#package-docs-as-github-pages) | [Motaz Marouf](https://github.com/devmtm) | TBD |
| [Next SSR, PWA and Static generator](#next-ssr-pwa-and-static-generator) | [Amro Salout](https://github.com/asalout) | TBD |
| [CSS & SVG Animations Libraries](#css--svg-animations-libraries) | [Anas Shamia](https://github.com/anas-shamia) | TBD |
| [GraphQL: Lighthouse & Prisma](#graphql-lighthouse--prisma) | [Yasir Awad](https://github.com/yassir3wad), [Yusuf Meimeh](https://github.com/yusufMeimeh) | TBD |

## GraphQL: Lighthouse & Prisma
For many years, we try to figure out the best way to design/develop REST APIs. In this experments we try to figure out if GraphQL can really solve our problems, and decide if it will be used on our next Project or not!

We planed to test two different GraphQL usage: 1) using Prisma as a ORM replacment so we can query our database directly using GraphQL format. 2) using GraphQL as an API standard between our back-end and front-end/mobile clients.

### Outcomes
Code generation, GraphQL Playground and docs, Dynamic data and relation selection without back-end changes is awsome, but we did not feel comfirtable using GraphQL in PHP as in Node.js, the cummunity and the tools is more stable and have better development experiance. We also face some problems with subscriptions in the native mobile side.

### Next steps
1. Try GraphQL clients for Web, Android, and React Native
1. Test GraphQL auth flow, file uploads, and authrization
1. Learn from Node.js experiance and move it to PHP/Laravel
1. Keep eyes on the iOS sybscription issue

## Nova event-sourcing actions
While we admire using Nova for it's simplicity and powerful features, we decided to build one of our internal product using ES/CQRS. This experment aims to bridge the gap between Nova CRUD operation and ES/CQRS principles.

### Outcomes
We decided to hide the internal CRUD operations, and replace them with Custom Actions, we extended the current Nova action so it can be Mapped to Events so we can save them in our Events store. Think of Nova Actions as your CQRS Commands.

### Next steps
1. Deliver default CUD implementation.
1. Customize the Nova UI to support custom actions.
1. Customize the Nova UI to support custom creation actions.
1. Make sure that Nova projection can re-create the current state.
1. Test Prisma against complex queries.

## Stress and Perfomance testing
TBD

## .Net Core DDD & CQR
TBD

## Package docs as Github pages
TBD

## Next SSR, PWA and Static generator
TBD

## CSS & SVG Animations Libraries
TBD
