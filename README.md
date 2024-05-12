# TypeScript
Some TypeScript Projects

React, Vue, Angular

## React by TypeScript

1. create project:
```Node.js
npx create-react-app react-typescript-demo --template typescript

yarn start
```
yarn test
yarn eject
yarn start

#### pass vars to component.
###### A. By props
Greet.tsx
```typescript
type GreetProps = {
    name: string
}
export const Greet = (props: GreetProps) => {
    return (
        <div>
            <h2>Welcome {props.name}! You have 10 unread messages.</h2>
        </div>
    )
}
```
App.tsx
```typescript
<Greet name='xxx' />
```






















































































