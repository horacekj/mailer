# Simple e-mail sender

Send e-mail to multiple recipients via FI MUNI SMTP.

This scripts sends e-mail message to multiple recipients as separate e-mail
for each recipient with its own To: header.
 * E-mail format: html with headers (see example).
 * Recipients format: text file with each address at separate line.
E-mail is sent as multipart message with html and text version too. Text version
is generated via pandoc from html.

## Example

You may try this example:

```
$ ./mailer xhorace4 example-rec.txt example-body.html
```
