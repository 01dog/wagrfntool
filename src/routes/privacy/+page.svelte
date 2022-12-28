<script>
	import Link from '$lib/components/helpers/Link.svelte';
</script>

<div class="flex flex-col justify-center">
	<h1 class="text-5xl font-bold text-center">privacy policy</h1>
	<p class="py-6 text-lg">wagrfnfinder.com ("site") primarily uses three services:</p>
	<ul class="list-disc text-lg" style="list-style-position: inside;">
		<li>
			<Link href="https://supabase.com/privacy" color="link-info">supabase</Link> to handle authentication
		</li>
		<li>
			<Link href="https://vercel.com/legal/privacy-policy" color="link-info">vercel</Link> for hosting
		</li>
		<li>
			<Link href="https://fly.io/legal/privacy-policy/" color="link-info">fly.io</Link> as a proxy for
			the RFN tool
		</li>
	</ul>
	<p class="py-3 text-lg">their privacy policies can be found at the links above.</p>
	<p class="py-3 text-lg">
		this site does not store any user data on its own. all data is stored with the providers above.
	</p>
	<p class="py-3 text-lg">
		this site uses cookies for authentication purposes only. no tracking, marketing, or other third
		party cookies are used.
	</p>
</div>
