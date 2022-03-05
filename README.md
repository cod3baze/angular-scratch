# Angular Scratch

> angular study

Angular é uma plataforma de desenvolvimento que permite a criação de aplicações web. Escrita em Typescript.

- framework baseado em components
- coleções de bibliotecas built-in. ex: routing, forms management..

## Entendendo angular

- Principais features e concepts:

  - Components
  - Templates
  - Directives
  - Dependency injection

### Components

- são blocos de códigos que compõe uma aplicação.
- um componente contém uma class em Typescript com o decorator `@Component()`, um HTML Template e os estilos.
  - o decorator `@Component()` define o nome do componente e o HTML Template e os estilos que definem a aparência da página.

  ```typescript
  @Component({
    selector: 'hello-world',
    template: `
      <h1>Hello World</h1>
      <p>This is my first component!</p>
    `,
    styleUrls: ['./app.component.css']
  })
  export class HelloWorldComponent {
    // o código dessa classe define o comportamento do component
  }
  ```

### Templates

todo component tem um *Template* HTML que declara como esse component é renderizado!

**templates** podem ser definidos inline ou em arquivos separados
