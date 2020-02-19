<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Us"
      subtitle="About Us"
      image="/cloud4freelogo.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
			<h3>ABOUT</h3>
			<p>The purpose of this blog is to show you what you can do by using only the "Free Tier" or "Always Free" layer from different cloud providers.</p>
			<p>We will use some sample applications to show how to make these applications available on the internet using several cloud computing providers available today, with no cost involved or at least with minimal cost (you will see that some providers provide free resource hours and not the resource as a whole, and this can result in a minimal cost).</p>
			<p>It is important to note that the rules for the free tier "Free Tier" and "Always Free" can change at any time, as the providers are the holders of these rules.</p>
			<p>If you find that any of the posts on this blog are not correct with the charges for the services listed in the post, contact us so we can update the material.</p>
			<p>It is not the purpose of this blog to make any kind of comparison in relation to providers and their services. We will only show you the different ways to structure and make available sample applications using free resources provided by the providers.</p>
			<p>Likewise, sample applications should not be used as a basis for developing your applications, as they may not implement your security, compliance, or even architecture requirements.</p>
			<p>Remember that because we use free services, which are limited in terms of computational capacity, the available application may not have high availability or adequate performance to serve a large mass of users</p>
			<p>The objective is to simply encourage you to put your ideas into practice in an economical way so that you can show your prototypes to others.</p>
        </div>
      </template>
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>

