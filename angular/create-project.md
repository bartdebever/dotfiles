# Creating a new Angular project

## Starting commands
```
ng new PROJECT-NAME --style=scss
```

## Angular Material

```
npm install --save @angular/material @angular/cdk @angular/animations
```

Follow the instructions [for Material Angular](https://material.angular.io/guide/getting-started#step-2-configure-animations).

## Ng Bootstrap

```
npm install --save @ng-bootstrap/ng-bootstrap
```

```typescript
import {NgbModule} from '@ng-bootstrap/ng-bootstrap';

@NgModule({
  ...
  imports: [NgbModule, ...],
  ...
})
export class YourAppModule {
}
```

## FontAwesome

```
npm install --save @fortawesome/angular-fontawesome
npm install --save @fortawesome/free-solid-svg-icons
npm install --save @fortawesome/fontawesome-svg-core
```

Further [instructions](https://fontawesome.com/how-to-use/on-the-web/using-with/angular)
