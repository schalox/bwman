**bwman**  (bashword  manager) is a password manager for bash. It keeps passwords
in a gpg-encrypted text file. Single action is allowed per invocation.

Before  using  bwman,  you  must create yourself a gpg key, which will be used
when encrypting the password-file.

    gpg2 --gen-key

Then create a file named bwman.asc, put it in ~/.local/share/bwman/ and
encrypt it with gpg. This will be your password-file.

    mkdir ~/.local/share/bwman

    touch ~/.local/share/bwman/bwman.asc

    gpg2 --encrypt --armor --recipient GPG-USERNAME \
    ~/.local/share/bwman/bwman.asc

Now you can start adding your passwords to the password-file with the **-a** switch.
You can also edit the password-file directly with the **-e** switch.

For more information, check the man-page and the config-file.
