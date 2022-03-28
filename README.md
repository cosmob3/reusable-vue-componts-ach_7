# CPNT-262 / Achievement 7 - Reusable Vue Components / Bryan Velasco

## TODO

- Create a reusable card component
  - title
  - text
  - X cta button
  - image
  - tags
- Set up props to pass information to the card component from the parent component/page
- Use v-if to render a tag list
- On your parent page (index.vue or App.vue), add an array of objects that contains information for a card
  - 3 cards
  - 1 of them must not have a tag array

## My Process

- Looked at what I would need to create and saw if those could be smaller components within a bigger component.

- I decided to make the `cta-button` and the `tags` into their own components.

- Made the button, I tested it out and it took up the width of the screen. Hope I can fix it later once its inside a component.
