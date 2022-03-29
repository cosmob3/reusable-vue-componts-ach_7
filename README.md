# CPNT-262 / Achievement 7 - Reusable Vue Components / Bryan Velasco

**Attributions**

- Photo of [Mountain by Aleksey Kuprikov](https://images.pexels.com/photos/3551214/pexels-photo-3551214.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260) from Pexels

- Photo of [Airplane by Alexey Demidov](https://images.pexels.com/photos/11341064/pexels-photo-11341064.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260) from Pexels

- Photo of [Boat in Water by Salvador Ortegarrieta](https://images.pexels.com/photos/11282403/pexels-photo-11282403.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940) from Pexels

## TODO

- Create a reusable card component

  - X title
  - X text
  - X cta button
  - image
  - X tags

- X Set up props to pass information to the card component from the parent component/page

- Use v-if to render a tag list

- X On your parent page (index.vue or App.vue), add an array of objects that contains information for a card
  - X 3 cards
  - X 1 of them must not have a tag array

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
  - X images
  - X tags

  Therefore,

  - X button can remain a component

- Used Props and slots to add the title and text for the cards so that they can be changed from the `index.vue` page

## TODO

- X Finished tags
- X image
- X v-if

- Ended up putting the tags right in the `index.vue` page

- Was messing around and I was able to maka my buttons work to show more content. Used `v-if` and `v-else-if`. Click them! They should work!

- Could not figure out how to make the last card the same size as the rest

- Finally added images
