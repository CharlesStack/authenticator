# authenticator
Sample Delphi code implementing Google Authenticator TOTP 

I'm pretty sure that some of this code is licensed until GPL. Thinking the attributes are still in place.
I'm licensing my code under the MIT license.  

# What still needs to be done?
The core value that needs to be set is the secret_key.  Obviously, what's here is bogus.  
Normally, you'd want to supply a way to parse the URL used by Google Authenticator and store the relevant info into a database.  That was beyond the scope of this simple project.

You may want to add a QRCode scanner as well to extract the secret and store it securely should you ever forget it,

And, you'll probably want to add a way to manually enter the information.  Again, it was outside the score of this simple demonstrator.
