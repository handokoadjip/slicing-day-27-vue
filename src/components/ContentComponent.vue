<template>
  <section class="my-0 my-lg-4">
    <div class="container">
      <div class="row">
        <div class="col-6 col-lg-4 mb-4" v-for="(list, index) in lists" :key="index" :id="list.name">
          <div class="wrapper position-relative mb-3 mb-lg-0">
            <figure class="m-0">
              <img class="img-fluid w-100 h-image-300px" :src="list.image" :alt="list.name" />
            </figure>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/img-2.jpg"),
          name: "image-2",
        },
        {
          image: require("@/assets/source/image/img-3.jpg"),
          name: "image-3",
        },
        {
          image: require("@/assets/source/image/img-4.jpg"),
          name: "image-4",
        },
        {
          image: require("@/assets/source/image/img-5.jpg"),
          name: "image-5",
        },
        {
          image: require("@/assets/source/image/img-6.jpg"),
          name: "image-6",
        },
        {
          image: require("@/assets/source/image/img-7.jpg"),
          name: "image-7",
        },
        {
          image: require("@/assets/source/image/img-8.jpg"),
          name: "image-8",
        },
        {
          image: require("@/assets/source/image/img-9.jpg"),
          name: "image-9",
        },
        {
          image: require("@/assets/source/image/img-10.jpg"),
          name: "image-10",
        },
      ]
    }
  }
}
</script>