<script>
	export let measureId;
</script>

<svelte:head>
	<meta name="google-site-verification" content="voiTglhkD6CY7DlWTV_7hcsuZIVis_8pL05_c8hdCJ0" />
	<!-- Global site tag (gtag.js) - Google Analytics -->
	<script
		async
		src="https://www.googletagmanager.com/gtag/js?id={measureId}"></script>
	<script>
		window.dataLayer = window.dataLayer || [];
		function gtag() {
			dataLayer.push(arguments);
		}
		gtag("js", new Date());
		gtag("config", measureId);
	</script>
	<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3250259365382047"
					crossorigin="anonymous"></script>
</svelte:head>