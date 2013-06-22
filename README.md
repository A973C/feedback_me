jQuery Feedback Plugin
===========

Description:
=====

This jQuery plug-in allows the user to easily add animatable feedback dialog that slides from the side of the screen.
If you are using this plugin it would be nice if you drop me an email to vedmack@gmail.com with some feedback.


Features:
=====

  - Bootstrap support 
  - jQuery UI themes support
  - RTL support
  - All labels are customizable


Usage:
=====

```javascript
$(document).ready(function(){
  fm_options = {
		bootsrtap : true,
		feedback_url : "send_feedback"
	};

	fm.init(fm_options);
});
```


* jQueryUI
* bootsrtap
* show_email
* name_label
* email_label
* message_label
* submit_label
* title_label
* trigger_label

Default settings :

```javascript
  	var default_options = {
			jQueryUI : false,
			bootsrtap : false,
			show_email : false,
			name_label : "Name",
			email_label : "Email",
			message_label : "Message",
			submit_label : "Send",
			title_label : "Feedback",
			trigger_label : "Feedback"
		};
```

License
=====

Copyright 2013
Licensed under the MIT License (just like jQuery itself)



[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/b6da00ccf307b6c278c41ba942e9af7c "githalytics.com")](http://githalytics.com/vedmack/feedback_me)
