```markdown
# Introduction to React

React is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. Complex React applications usually require the use of additional libraries for state management, routing, and interaction with an API.

## Key Features

*   **Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes.

*   **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs.

*   **Learn Once, Write Anywhere:** We don’t make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code.

## Example

Here's a simple React component:

```javascript
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

const element = <Welcome name="Sara" />;
ReactDOM.render(
  element,
  document.getElementById('root')
);
```

## Further Reading

*   [Official React Documentation](https://reactjs.org/)
*   [React Tutorial](https://reactjs.org/tutorial/tutorial.html)
```
```markdown
# Introduction à React

React est une bibliothèque JavaScript pour la construction d'interfaces utilisateur. Elle est maintenue par Facebook et une communauté de développeurs individuels et d'entreprises. React peut être utilisé comme base dans le développement d'applications monopages ou mobiles. Les applications React complexes nécessitent généralement l'utilisation de bibliothèques supplémentaires pour la gestion de l'état, le routage et l'interaction avec une API.

## Caractéristiques principales

*   **Déclaratif :** React rend la création d'IU interactives indolore. Concevez des vues simples pour chaque état de votre application, et React mettra à jour et rendra efficacement les composants appropriés lorsque vos données changeront.

*   **Basé sur les composants :** Construisez des composants encapsulés qui gèrent leur propre état, puis composez-les pour créer des IU complexes.

*   **Apprenez une fois, écrivez partout :** Nous ne faisons pas d'hypothèses sur le reste de votre pile technologique, vous pouvez donc développer de nouvelles fonctionnalités dans React sans réécrire le code existant.

## Exemple

Voici un composant React simple :

```javascript
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

const element = <Welcome name="Sara" />;
ReactDOM.render(
  element,
  document.getElementById('root')
);
```

## Lectures complémentaires

*   [Documentation officielle de React](https://reactjs.org/)
*   [Tutoriel React](https://reactjs.org/tutorial/tutorial.html)
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._