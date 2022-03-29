# CPNT-262 / Achievement 7 - Reusable Vue Components / Bryan Velasco

## TODO

- Create a reusable card component

  - X title
  - X text
  - X cta button
  - X image
  - X tags

- X Set up props to pass information to the card component from the parent component/page

- Use v-if to render a tag list

- On your parent page (index.vue or App.vue), add an array of objects that contains information for a card
  - 3 cards
  - 1 of them must not have a tag array

## My Process

- Looked at what I would need to create and saw if those could be smaller components within a bigger component

- I decided to make the `cta-button` and the `tags` into their own components

- Made the button, I tested it out and it took up the width of the screen. Hope I can fix it later once its inside a component

- Created tag component!

- Went ahead and created a card component. Added the `cta-button` and `tags` to it. Used a grid box to display 3 card columns. Made all the other parts static but I'm seeing that I'll have to something more dynamic to change out the image and title.

- Going to work on props

---

- What things do I want to be able to change from the `index.vue` page

  - X title
  - X text
  - images
  - tags

  Therefore,

  - X button can remain a component

- Used Props and slots to add the title and text for the cards so that they can be changed from the `index.vue` page
