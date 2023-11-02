# Readings: Forms and JS Events

## Why is this important?

- Forms and events are important because they go hand in hand on allowing users to input data and having the site dynamically process and output that information.  Example, user inputs information and it shows up on a table on the site.

## HTML Forms

### Your first Web Form.  How to Structure a Web Form

1. Forms are important because they allow users to input data that the website can dynamically use.

2. Some key things to kep in mind when ic comes to user experience are "The bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need" [source](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

3. 

    1. `<form>` Defines the form, also can have special attributes but they're optional.

    2. `<label>` Which is pretty self-explanatory, it labels what the text area requires

    3. `<input>` Changes the of user input field on the site.  

    4. `<textarea>` Is the actual place that the user will type their input into the form

    5. `<button>` Will allow the user to submit their data 

## Learn JS



### Intro. to Events

1. Events are similar to triggers or a cause and effect.  When something occurs something else will trigger or happen.

2. You need to provide the type of event can listen to and a function to call when the event happens when using the `addEventListener()` method.

3. "Event objects provide extra features and information" [source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_objects).  The target within the event object is useful because it only applies to the element that the event occured on.  

4. "Event bubbling describes how the browser handles events targeted at nested elements" events start on most nested elements and works it's way out while event capture is reversed.  Meaning: events start on elements that are least nested within the document and works its way in. [source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_bubbling)

## Things I want to know more about

- When you say `"click"` for the `btn.addEventListener()` does the computer automatically recognize click.

## In class lecture

- 