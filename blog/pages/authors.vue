<template>
  <div id="authors-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Authors"
      subtitle="Authors"
      image="/cloud4freelogo.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <img src="/collaborators/felippe.jpg">
    			<h2>Felippe Augusto de Oliveira Neto (FAON)</h2>
          <h3>Sao Paulo, Brazil</h3>
    			<p>I have 16 years of experience in Oracle Consulting, implementing on-premise portal solutions, access control, and identity management for clients in Brazil.
    			<p>After the years of consulting, I dedicated the following 3 years to creating and publishing tutorials, videos about the use case for the platform service (PaaS) Oracle Identity Cloud Service in the Oracle User Assistance team.</p>
    			<p>From 2019, I focused on studies and learning at the various cloud infrastructure providers (IaaS).</p>
    			<p>With the studies, I obtained the certifications of architect Oracle Cloud Infrastructure and Amazon Web Services in the beginning of 2020.</p>
          <p>Nowadays I work for TOTVS, in the retail LOB, as software developer specialist for Omni Channel.</p> 
          <table cellspacing="10">
    				<tbody>
    					<tr>
    						<td align="center"><img src="/collaborators/aws-certified-logo_color-horz_180x30.jpg"><br><img src="/collaborators/cloud-practitioner-tag_180x16.jpg"><br><img src="/collaborators/solutions-architect-associate-tag_180x16.jpg"></td>
    						<td align="center"><img src="/collaborators/oracle-cloud-infrastructure-2019-architect-associate.png"></td>
    					</tr>
    				</tbody>
    			</table>
    			<br>
    			<a href="mailto:faonbr@gmail.com">Email</a>&nbsp;-&nbsp;<a href="https://www.linkedin.com/in/felippe-augusto-de-oliveira-neto/" target="_blank">Linked</a>
    			<hr>
    			<h2>Robert Lavallie</h2>
          <h3>New York, USA</h3>
    			<p>Robert is a great friend of mine. We worked together in the User Assistance team. We used to say that we were "Partners in Crime" (Partners in Crime, in English) because each completes the other's thinking and vice versa.</p>
    			<p>Robert collaborates with this blog by reviewing the posts and including his detailed view of the use cases, as well as helping to translate the site into English.</p>
    			<p>He's also going to write about Kubernetes.</p>
    			<br>
    			<a href="mailto:tutorman10461@gmail.com">Email</a>&nbsp;-&nbsp;<a href="https://www.linkedin.com/in/robert-la-vallie-37725243/" target="_blank">Linked</a>
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
