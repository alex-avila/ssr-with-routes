<template>
  <div>
    <div class="about-yellow">
      <h1 class="title is-1 about-title has-text-centered">About Us</h1>
    </div>
    <content-container>
      <div class="story">
        <h1 class="title is-2">Shoes made sustainably.</h1>
        <img
          src="@/assets/about-page-story.jpg"
          alt="Pile of Rothy's shoes."
          class="story__img"
        >
        <p class="is-size-3 has-text-weight-light">
          A wardrobe staple that goes with pretty much everything. Lightweight comfort.
          A shoe you'd be happy to keep on all day. In Rothy's style, comfort and versatility
          coexist in the first sustainable shoe as atylish as it is comfortable; look good in you
          Rothy's and feel good about your Roghy's. That's something you don't see every day in fashion.
        </p>
      </div>
    </content-container>
  </div>
</template>

<style>
.about-yellow {
  background: rgb(235, 209, 145);
  padding: 3em 0;
}

.story {
  padding: 2em 0 3em;
  text-align: center;
}

.story__img {
  margin: auto;
}
</style>
