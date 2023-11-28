# Reading 02 State and Props

## Why this is important?

- The react lifecycle is important in order to dynamically control actions of the website based on certain events.  "If you want actions performed after the rendering of the site is complete"

- Identifying the differences between State and Props is important since they have different use cases and applications.

## React lifecycle 

1. Render happens first.

2. A constructor for a component is the first thing that happens before the mounting phase begins.

3. `constructor`, `render`, `reactUpdates`, `componentDidMount`, `componentWillUnmount`.

4. `componentDidMount` is used for any action need after the component is rendered.

## React State vs Props

1. You can pass things that functions might need, similar to arguments. Ex: "Initial Count, Titles/Subtitles? [source](https://www.youtube.com/watch?v=IYvD9oBCuJI)

2. "Props you pass to a component while state is handled inside of a certain component. State updated inside component, props updated outside component. When you update state it will rerender the app."

3. You re-render the application once the user has performed an action and the state has changed. 

4. You can store dynamic values "Counter application".  Form inputs. 

## Things I want to learn

- How do you use state?

- Does the entire application need to update if state is changed or just the component?