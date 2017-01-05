# updtr-mailinglist
A Mailing List based on PHP that allows an adminstrator to add or delete e-mail-adresses from the list. Mails by trusted senders will be forwarded immediatly (cronjob) or the administrator can send the mails manually.

##usage
* Use config.php for general settings
* Use mailinglist class to  in your frontend to display, delete or send the mails.
* add autosend.php to any cronjob so mails by trusted senders will be sent automatically
** the output format is a json dictionary you can use with zapier.com for example
 
