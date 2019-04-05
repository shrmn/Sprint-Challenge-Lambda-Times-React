- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

>To validate that our props are the type we expect them to be. This is important in preventing errors from occurring in our code.

- [ ] Describe a life-cycle event in React?

>The React lifecycle is comprised of 3 phases. Mount, Update, and Unmount. When an app first loads, React will mount components. When the state is updated or another trigger occurs, the components whose content were affected by the update in state will update. Unmount occurs when a component is no longer necessary. React unmounts (or removes) it from the virtual DOM.

>This is the meat and potatoes of React. We give it state, components, and methods for determining when and how to use them. This process is the React lifecycle. The birth, life, and death of React components. We have it because otherwise we don't have a reactive application. We have a static webpage.

- [ ] Explain the details of a Higher Order Component?

>HOCs are functions which take in components as arguments and return new components. This lets us take chunks of reusable logic and apply them as desired to various components instead of rewriting the logic into each component. Keeping it DRY.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

>Inline CSS - This method lets you more easily understand what styles are in each component

>CSS Modules - Lets you import CSS files into your components. You can organize your styles by component but write plain old CSS. 

>Styled Components - It's a convenient library of pre-built components which already have styling. 