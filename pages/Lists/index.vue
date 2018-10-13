<template>
	<div class = "Lists-Page">
    <v-layout>
      <v-flex text-xs-center>
		<section class = "featured-posts">
<nuxt-link :to="'/Lists/' + 1" class = "post-preview">
  <article >
   <div class = "post-thumbnail" style = "background-image: url(https://www.indiasopinion.in/wp-content/uploads/2017/06/indian-oil-corporation-petrol-diesel-price-decreased.jpg)"></div>
   <div class = "post-content">
   <h1>Who benefitted from increase in taxes on Petrol & Diesel?</h1>
   <p>By Rakesh Dubbudu
September 14, 2018</p>

   </div>
   </article>
  </nuxt-link>

  <nuxt-link :to="'/Lists/' + 2" class = "post-preview">
  <article >
   <div class = "post-thumbnail" style ="background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Women_in_Deogarh_morning%2C_Orissa%2C_India.jpg/250px-Women_in_Deogarh_morning%2C_Orissa%2C_India.jpg)"></div>
   <div class = "post-content">
   <h1>Conviction rate of Sec 498-A cases is among the lowest of all IPC Crimes</h1>
   <p>By Rakesh Dubbudu
September 15, 2018
1</p>
   </div>
   </article>
  </nuxt-link>

  <nuxt-link :to="'/Lists/' + 3" class = "post-preview">
  <article >
   <div class = "post-thumbnail" style ="background-image: url(http://www.babushahi.com/upload/image/nri-vote-india-logo-550x410.jpg)"></div>
   <div class = "post-content">
   <h1>Less than 0.1% NRIs registered as Voters, more than 96% from Kerala</h1>
   <p>By Rakesh Dubbudu
September 13, 2018</p>
   </div>
   </article>
  </nuxt-link>

  <nuxt-link :to="'/Lists/' + 4" class = "post-preview">
  <article >
   <div class = "post-thumbnail" style ="background-image: url(https://qph.fs.quoracdn.net/main-qimg-db99864377d80c22a26cbb4636c2dab0-c)"></div>
   <div class = "post-content">
   <h1>Here is how you can claim a full refund of a ‘Mutilated Currency Note’</h1>
   <p>By Rakesh Dubbudu
September 8, 2018</p>
   </div>
   </article>
  </nuxt-link>
</section>
</v-flex>
</v-layout>
</div>
	
 </template>
 <script>
   export default {
     layout: 'RestPages'
   }
 </script>

     
    



 <style scoped>
 	.Lists-Page {
  display: flex;
  justify-content: center;
  align-items: center;
 
}
.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.post-preview {
  border: 1px solid #ccc;
  box-shadow: 0 2px 2px #ccc;
  background-color: white;
  width: 90%;
}

a {
  text-decoration: none;
  color: black;
}

@media (min-width: 850px) {
  .post-preview {
    width: 400px;
    margin: 10px;
  }
}

.post-thumbnail {
  width: 100%;
  height: 200px;
  background-position: center;
  background-size: cover;
}

.post-content {
  padding: 10px;
  text-align: center;
}

a:hover .post-content,
a:active .post-content {
  background-color: #ccc;
}



 </style>
