Features :

With this plugin, you can protect the registration process with a CAPTCHA. If a user wants to register, he has to read the letters from the image and enter them for verification. This prevents automated registrations with bots.

CAPTCHA stands for Completely Automated Public Turing-Test to Tell Computers and Humans Apart.

To learn more about CAPTCHA read this.

Installation :

1 : Unpack and upload the files into the folder : /plugins/captcha/

2 : Go into the administration panel, then tab "Plugins", click the name of the new plugin, and at bottom of the plugin properties, select "Install all".

3 : Then in the same page, check if this plugin require new tags in the skin files (.TPL).
If yes, then open the skin file(s) with a text editor, and add the tag(s).

Notes :

You have to insert the following tags to the users.register.tpl:

{USERS_REGISTER_VERIFYIMG} (for the image)
{USERS_REGISTER_VERIFYINPUT} (for the input field)

Big thanks to :

- Edward Eliot for his genius PhpCaptcha class

Copyrights :

- PhpCaptcha is licensed under the Free BSD license.

History :

v100 (first public release) 