<template>
  <div>
    <img src="https://cdn.shopify.com/s/files/1/0877/4986/collections/womens-header_23cc4594-155b-47be-8c1f-1c85284a40d0.jpg?v=1537191378">
    <content-container>
      <div class="info">
        <div>
          <h2 class="title is-2">Made from recycled water bottles.</h2>
          <span class="small-separator"/>
          <p class="is-size-4">It took us three years of research to create a shoe that's comfortable, beautiful, and most importantly, sustainable.</p>
        </div>
        <div :style="infoImgStyle">
          <div class="bottle-info">
            <p class="heading">WATER BOTTLES REPURPOSED</p>
            <span class="title is-2">18,702,792</span>
          </div>
        </div>
      </div>
    </content-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      infoImgStyle: {
        background: `url(http://cdn.shopify.com/s/files/1/0877/4986/files/homepage-material-desktop.jpg?v=1505922585)`,
        backgroundPosition: 'right',
        backgroundSize: 'cover',
        height: '350px'
      }
    }
  }
}
</script>

<style>
.info {
  text-align: center;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  align-items: center;
  gap: 3em 1em;
  padding: 2em 0;
}

.small-separator {
  height: 1px;
  display: block;
  width: 50px;
  background: black;
  margin: 1em auto;
}

.bottle-info {
  padding: 1em;
  text-align: left;
}
</style>
