<html>
<body>

<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DVF00000ASfTt',
				'NAT_Chat_Web',
				'https://fleetcorna--uat.sandbox.my.site.com/ESWNATChatWeb1730916725514',
				{
					scrt2URL: 'https://fleetcorna--uat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://fleetcorna--uat.sandbox.my.site.com/ESWNATChatWeb1730916725514/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html> 
