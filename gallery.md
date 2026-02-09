---
layout: page
title: Gallery
image_base: /assets/image26/gallery/
---
<style>


body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
}

.gallery {
  --size: 85hv;
  display: grid;
  grid-template-columns: repeat(1, var(--size));
  grid-auto-rows: var(--size);
  margin-bottom: var(--size);
  place-items: start center;
  gap: 5px;
  overflow: visible;
  
  &:has(:hover) img:not(:hover),
  &:has(:focus) img:not(:focus){
    filter: brightness(0.75) contrast(0.75);
  }

  & img {
    object-fit: cover;
    width: calc(var(--size) * 2);
    height: calc(var(--size) );
    clip-path: polygon(
      50% 0%,
      100% 50%,
      50% 100%,
      0% 50%
    );
    transition: clip-path 0.25s, filter 0.75s;
    grid-column: auto / span 1;
    border-radius: 5px;

    &:hover,
    &:focus {
      clip-path:polygon(
        0% 0%,
        100% 0%,
        100% 100%,
        0% 100%
      );
      object-fit: contain; 
      z-index: 1;
      overflow: visible;
      transition: clip-path 0.3s, filter 0.3s;
    }
    
    &:focus {
      outline: 1px dashed black;
      outline-offset: -5px;
    }
  }
}





</style>

<!-- Here, we’ll post the awesome photos taken during this edition of the workshop! -->

<article class="gallery">
  <img src="{{ page.image_base }}social_lunch.jpeg" alt="Picture at social lunch on Sunday, in Casal de Barri Es Jonquet" />
  <img src="{{ page.image_base }}social_lunch_2.jpeg" alt="Picture at social lunch on Sunday, in Casal de Barri Es Jonquet" />
  <img src="{{ page.image_base }}es_jonquet.jpg" alt="Picture at the door of the welcoming event, in Casal de Barri Es Jonquet" />
  <img src="{{ page.image_base }}venue.JPG" alt="Venue" />
  <img src="{{ page.image_base }}working_project.jpeg" alt="Work in progres" />
  <img src="{{ page.image_base }}rafael.JPG" alt="Talk of the keynote speaker Rafael Prieto-Curiel" />
  <img src="{{ page.image_base }}luis_talk.jpeg" alt="Talk of the keynote speaker Luis Seoane" />
  <img src="{{ page.image_base }}carmen_talk.jpeg"  alt="Talk of the keynote speaker Carmen Cabrera" />
  <img src="{{ page.image_base }}project3.jpeg" alt="Work in progres" />
  <img src="{{ page.image_base }}hiking.jpeg"  alt="Hiking through Serra de Tamuntana" >
  <img src="{{ page.image_base }}group.JPG" alt="Group photo" />
  <img src="{{ page.image_base }}closing.JPG" alt="Closing event" />
  <img src="{{ page.image_base }}present3.jpeg" alt="Presentation of the project Centralized collective decision-making in nest-hunting ants..." />
  <img src="{{ page.image_base }}present4.jpeg" alt="Presentation of the project Attenuating contagion in the global trade network" />
  <img src="{{ page.image_base }}present6.jpeg" alt="Presentation of the project How voting in national and European Parliament ..." />
  <img src="{{ page.image_base }}oc_group.jpg" alt="OC group photo" />
</article>
