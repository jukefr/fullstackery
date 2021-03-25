<div align="center">
  <a href="https://github.com/jukefr/AnarchyX">
  <img width="100%;"  src="https://user-images.githubusercontent.com/2154296/112435645-4d0eaf80-8d45-11eb-815c-71fe018ab2b8.png">
  </a>
  <br>
</div>

a fast prototyping full stack boilerplate for javascript projects

idea:

use containers as "blocks"

that can be picked freely as modules

to create wanted architecture

rough example:

`stack.yml`
```yml
database:
    type: mongo or sql, postgres etc
backend:
    type: strapi or express, feathers, gql yoga etc
frontend:
    type: next or nuxt etc
```

which would then generate everything and bootstrap all thats needed to start mvping

modular design also allows easier maintaineance and contributions

must make sure i design it right form the getgo though to not waste time later down the line
