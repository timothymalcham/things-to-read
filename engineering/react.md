# React

- ### [Writing resilient components](https://overreacted.io/writing-resilient-components/)

  _Key take aways:_
  > If you’re not sure whether some state is local, ask yourself: “If this component was rendered twice, should this interaction  reflect in the other copy?” Whenever the answer is “no”, you found some local state.

- [React component composition](https://www.robinwieruch.de/react-component-composition/)
- [How are function components different from classes?](https://overreacted.io/how-are-function-components-different-from-classes)
- [Publishing a react component as an NPM module](https://parastudios.de/create-a-react-component-as-npm-module)
- [Build a swipeable list with react](https://malcoded.com/posts/react-swipeable-list)
- [Scheduling in react](https://philippspiess.com/scheduling-in-react/)
- [Using boolean React props](https://spicefactory.co/blog/2019/03/26/how-to-avoid-the-boolean-trap-when-designing-react-components/)
- [Testing stateful react function components with react testing library](https://www.robertcooper.me/testing-stateful-react-function-components-with-react-testing-library)
- [How to create an accessible react modal](https://levelup.gitconnected.com/how-to-create-an-accessible-react-modal-5b87e6a27503)
– [Using react for state management](https://kentcdodds.com/blog/application-state-management-with-react)
- [React as a UI runtime](https://overreacted.io/react-as-a-ui-runtime/)
- [How are function components different from classes](https://overreacted.io/how-are-function-components-different-from-classes/)
– [React interview questions](https://tylermcginnis.com/react-interview-questions/?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_131)
- [CRUV: Structure React apps in 4 directories and 3 files - James K Nelson](http://jamesknelson.com/cruv-react-project-structure/?utm_source=reactdigest&utm_medium=email&utm_campaign=featured)

### React Perf

- [Progressive React](https://houssein.me/progressive-react?utm_source=reactdigest&utm_medium=email&utm_campaign=featured)
- [Airbnb case study](https://medium.com/airbnb-engineering/recent-web-performance-fixes-on-airbnb-listing-pages-6cd8d93df6f4)
- [How to avoid React hooks performance pitfall](https://medium.com/@_m1010j_/how-to-avoid-this-react-hooks-performance-pitfall-28770ad9abe0)
– [5 things to speed up react app](https://www.thedevelobear.com/post/5-things-to-improve-performance/?utm_source=reactdigest&utm_medium=email&utm_campaign=featured)

### React Hooks

- [useHooks – daily hook recipes](https://usehooks.com/?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_138)
- [Simplify forms with react hooks](https://upmostly.com/tutorials/using-custom-react-hooks-simplify-forms/)
- [Getting hooked on react hooks](https://tech.okcupid.com/getting-hooked-on-react-hooks/)
- [Using react hooks with typescript](https://levelup.gitconnected.com/usetypescript-a-complete-guide-to-react-hooks-and-typescript-db1858d1fb9c)
- [Formal – hooks for forms](https://github.com/kevinwolfcr/formal)
- [How to avoid passing callbacks down](https://reactjs.org/docs/hooks-faq.html#how-to-avoid-passing-callbacks-down)
- [From redux to hooks](https://staleclosures.dev/from-redux-to-hooks-case-study/)
- [Complete guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/)
- [When to use react useRef and useLayoutEffect](https://dev.to/rleija_/when-to-use-react-useref-and-uselayouteffect-57kh)
- [Advanced React hooks](https://testdriven.io/blog/react-hooks-advanced/?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_157#.XLcod_Gltqo.reddit)
- [How do hooks really work?](https://www.netlify.com/blog/2019/03/11/deep-dive-how-do-react-hooks-really-work/?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_157)
- [How to use react context effectively](https://kentcdodds.com/blog/how-to-use-react-context-effectively)
- [React useReducer hook](https://www.robinwieruch.de/react-usereducer-hook/)
- [useReducer vs useState](https://www.robinwieruch.de/react-usereducer-vs-usestate/?utm_campaign=React%2BNewsletter&utm_medium=email&utm_source=React_Newsletter_159)


> The question is not “when does this effect run” the question is “with which state does this effect synchronize with”
>
> - useEffect(fn) // all state
> - useEffect(fn, []) // no state
> - useEffect(fn, [these, states])
>
> @ryanflorence on Twitter
