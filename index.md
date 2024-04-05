<html>

<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US';

			embeddedservice_bootstrap.init(
				'00D1x000000KJBR',
				'MessagininWebTEst28_03',
				'https://talixo--bigtestbox.sandbox.my.site.com/ESWMessagininWebTEst28031711637157640',
				{
					scrt2URL: 'https://talixo--bigtestbox.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://talixo--bigtestbox.sandbox.my.site.com/ESWMessagininWebTEst28031711637157640/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
