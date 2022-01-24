<!-- App.svelte -->
<script>
  import { router, link, route } from "svelte-routing";
  import Home from "./routes/home.svelte";
  import About from "./routes/about.svelte";
  export let url = "";
</script>

<h1>Anker {name}</h1>


<router url="{url}">
  <nav>
    <Link to="/">home</Link>
    <Link to="about">about</Link>
  </nav>
  <div>
    <route path="about" component="{about}" />
    <route path="/"><home /></route>
  </div>
</router>


		<p class=" bd-textblock-10 bd-content-element">
			<b> Because we need older members but not over 21 for the safety of our members.</b>&nbsp;
</p>
		<p class=" bd-textblock-15 bd-content-element">
    We also do monthly giveaways for battle passes for our members!
</p>

	<li><b>Requirements:</b>&nbsp;</li><li>Must have mic</li><li>Must have Discord</li><li>Must be over level 100 on COD Mobile</li>
	<div class="row">
  <div class="column">
	  <b><small>These are Orions socials and please donate!</small></b>
	  <br>
       <a>
	       href="https://www.paypal.com/paypalme/orioncrespo45">
<img src ="images/Paypal.png" alt="paypal" width="65" height="66">
</a>

	<a>
		href="https://twitter.com/orioncrespo10">
<img src="images/twitter--v2.gif" alt="twitter" width="65" height="66">
</a>

	<a>
		href="https://www.facebook.com/baize.riot">
<img src="images/faceb.svg" alt="facebook" width="65" height="66">
</a>
	  </div>
  <div class="column">

	 <a>
		 href="https://www.instagram.com/orioncrespo15/">
<img src="images/insta.jpeg" alt="instagram" width="65" height="66">
</a>

	  </div>
</div>






		<nft-card
  tokenAddress="0x495f947276749ce646f68ac8c248420045cb7b5e"
  tokenId="74910965659129920827967912483173887147949622782888675597174626338947519741953"
  network="mainnet"
  referrerAddress="0x495f947276749ce646f68ac8c248420045cb7b5e"
  >
</nft-card>
	<br>
	Contact Orion for prices to get your NFT listed on our page.

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
<center>
<h2>This is My youtube Channel. Go check it out!</h2>
<iframe width="560" height="315"
src="https://www.youtube.com/embed/KvbaVt_gQCY?controls=0&amp;start=9"
title="YouTube video player" frameborder="0" allow="picture-in-picture"
allowfullscreen></iframe>
</center>
