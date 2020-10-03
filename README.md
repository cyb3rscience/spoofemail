# spoofemail
This simple PowerShell code allows you to send a spoofed email from within your network.

Send-MailMessage -SmtpServer [yoursmtpserver] -From "[fromcorporateemailaddress]" -To "[toanothercorporateemailaddress]" -Subject "[Subject]" -Body "[Body]"

Replace the following before trying out on your lab enviroment (Disclaimer: We do not recommend you use this on production environment):

[yoursmtpserver]: with your smtp server
[fromcorporateemailaddress]: the email address you want to spoof from
[toanothercorporateemailaddress]: the destination email address you want to target
[Subject]: Subject of the email
[Body]: email body
