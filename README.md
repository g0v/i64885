i64885
======

A request tracking and notification system for legal aid.  Helping political victims in emergency situation.  


[Architecture]
victim->server
server->fb
link->server
server -> response to permerant link in fb
server -> response to mail
server -> response to text msg

[Ask for help]
victim-> server -> fb

[Notification]
fb->mail->lawyers
fb->post->browsed by lawyers

[Take issue]
Lawyers -> click fb link -> server -> accept
Lawyers -> click fb link -> server -> already taken
Lawyers -> click link in mail -> server -> accept / already taken
Lawyers -> click link in text message -> server -> accept / already taken

[Lawyer management]
Set area
Set period
Statistics

[Bidding system]
Conditions
timeout
abort
時效

[Feature]
Calendar
Details
