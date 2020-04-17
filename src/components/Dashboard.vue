<template>
<div class="main bg-color-1">
  <b-row>
    <b-col cols="3">
    <b-card-group deck class="mt-1">
  <b-card no-body header="Category" header-bg-variant="warning">
      <b-list-group-item href="#">Category 1</b-list-group-item>
      <b-list-group-item href="#">Category 2</b-list-group-item>
      <b-list-group-item href="#">Category 3</b-list-group-item>
  </b-card>
</b-card-group>
  </b-col>

  <b-col cols="9">
  <div>
    <b-card-group deck class="mt-1 mr-1">
      <b-card
        title="Card Title"
        img-src="https://i.picsum.photos/id/1047/3264/2448.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the bulk of the card's content.
        </b-card-text>
      </b-card>

      <b-card
        title="Card Title"
        img-src="https://i.picsum.photos/id/1047/3264/2448.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the bulk of the card's content.
        </b-card-text>
      </b-card>

      <b-card
        title="Card Title"
        img-src="https://i.picsum.photos/id/1047/3264/2448.jpg"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the bulk of the card's content.
        </b-card-text>
      </b-card>
    </b-card-group>
  </div>
  </b-col>
  </b-row>
</div>
</template>
