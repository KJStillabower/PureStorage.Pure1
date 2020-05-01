# PureStorage.Pure1
 Pure Storage Pure1 Module
<!-- wp:paragraph -->
<p>To help our customers I have written a module that makes it easy to connect to the Pure1 REST API with PowerShell.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The module is called&nbsp;<a href="https://www.powershellgallery.com/packages/PureStorage.Pure1">PureStorage.Pure1</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><em>To report issues or request new features, please enter them here:</em></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://github.com/PureStorage-OpenConnect/PureStorage.Pure1/issues">https://github.com/PureStorage-OpenConnect/PureStorage.Pure1/issues</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>For questions, <a href="https://codeinvite.purestorage.com/">join our Pure Storage Code Slack</a> team!</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>There are a couple of places you can download this. The best option is the&nbsp;<a href="https://www.powershellgallery.com/packages/PureStorage.Pure1">PowerShell gallery</a>! This allows you to use&nbsp;<a href="https://docs.microsoft.com/en-us/powershell/module/powershellget/install-module?view=powershell-6">install-module</a>&nbsp;to automatically install the module. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>To install:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">install-module PureStorage.Pure1</pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>To load the module:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">import-module PureStorage.Pure1 </pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>To update:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">update-module PureStorage.Pure1</pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>Blog post on Pure1 REST Authentication:</p>
<!-- /wp:paragraph -->

<!-- wp:core-embed/wordpress {"url":"https://www.codyhosterman.com/2019/12/pure1-rest-api-authentication-made-easy/","type":"wp-embed","providerNameSlug":"cody-hosterman","className":""} -->
<figure class="wp-block-embed-wordpress wp-block-embed is-type-wp-embed is-provider-cody-hosterman"><div class="wp-block-embed__wrapper">
https://www.codyhosterman.com/2019/12/pure1-rest-api-authentication-made-easy/
</div></figure>
<!-- /wp:core-embed/wordpress -->

<!-- wp:paragraph -->
<p>Use either get-help or get-command to see the details:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":6205,"sizeSlug":"large"} -->
<figure class="wp-block-image size-large"><img src="https://www.codyhosterman.com/wp-content/uploads/2019/12/image-16.png" alt="" class="wp-image-6205"/></figure>
<!-- /wp:image -->

<!-- wp:image {"id":6209,"sizeSlug":"large"} -->
<figure class="wp-block-image size-large"><img src="https://www.codyhosterman.com/wp-content/uploads/2019/12/image-17.png" alt="" class="wp-image-6209"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p><strong>Comment on Versioning</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Versions numbering w.x.y.z (for example 1.2.0.0)</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>W is iterated for large updates</li><li>X is iterated for new cmdlets</li><li>Y is iterated for new functions to existing cmdlets</li><li>Z is iterated for bug fixes</li></ul>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Latest version 1.0.1.1 (April 30th, 2020)</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>See  version details: <a href="https://github.com/PureStorage-OpenConnect/PureStorage.Pure1/projects/1">https://github.com/PureStorage-OpenConnect/PureStorage.Pure1/projects/1</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>New features:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Continuation Token Support</li><li>-Debug support</li><li>Handle exceeding rate limits</li><li>Get-Help examples</li><li>Support for varied REST versions in global parameter $Global:PureOneRestVersion</li><li>Support for customer query result limits in global parameter $Global:PureOneRateLimit</li><li>Various internal improvements</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><strong>Bug Fixes:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Get-PureOneVolumeSnapshot fails at scale</li><li>Volume filter didn't work for Get-PureOneVolumeSnapshot</li><li>No Parameter sets/mandatory parameters</li><li>Defaulting to REST 1.0 only</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Cmdlets:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>New-PureOneCertificate</li><li>Get-PureOnePublicKey</li><li>New-PureOneJwt</li><li>New-PureOneRestConnection </li><li>Get-PureOneArrays </li><li>New-PureOneRestOperation </li><li>Get-PureOneArrayTags </li><li>Set-PureOneArrayTags </li><li>Remove-PureOneArrayTags </li><li>Get-PureOneArrayNetworking </li><li>Get-PureOneMetricDetails </li><li>Get-PureOneMetrics </li><li>Get-PureOneVolumes </li><li>Get-PureOnePods </li><li>Get-PureOneVolumeSnapshots </li><li>Get-PureOneFileSystems </li><li>Get-PureOneFileSystemSnapshots </li><li>Get-PureOneArrayBusyMeter</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><br><br></p>
<!-- /wp:paragraph -->
