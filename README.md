# WordPress Author Box Plugin

This is a plugin that adds an author box to the end of your posts, showing off the authors name, description, website link and gravatar powered avatar.

As of version 1.3 the following input boxes were removed: aim/yim/jabber, and the following input boxes were added: twitter/facebook/google+/linkedin/dribbble/github

== Frequently Asked Questions ==

= Will there ever be more options added? =

Yes, I do have plans on adding more options for this plugin. For instance, I plan on adding a page in the WordPress admin panel for you to be able to edit the CSS so the author box can be styled to fit with your theme design.

= What are the default CSS codes? =

As of version 1.3, the css is contained in it's own style.css file within the plugin folder instead of directly added to the html of your web page.

You can copy/paste the below css codes into your themes CSS file and adjust them accordingly in order to override the css that's been added with the plugin.

	.guerrillawrap {
		background: #f8f8f8;
		-webkit-box-sizing:border-box;
		-moz-box-sizing:border-box;
		-ms-box-sizing:border-box;
		box-sizing:border-box;
		border: 1px solid #dadada;
		float: left;
		padding: 2%;
		width: 100%;
	}

	.guerrillagravatar {
		float: left;
		margin: 0 10px 0 0;
	}

	.guerrillatext {
	}

	.guerrillatext h4 {
		margin: 0 0 0 0;
	}

	.guerrillatext p {
		margin: 5px 0 12px 0;
	}

	.guerrillasocial {
		float: left;
		width: 100%;
	}

== Installation in WordPress ==

1. Upload 'guerrilla-author-box.php' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
