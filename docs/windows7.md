# Windows 7

Windows 7 is still supported until 14th January 2020 so might as well make good use of it for the next (as of time of writing) year and a half!

## Chocolatey

As admin, to make everything else easier:

```
cinst -y sudo
```

## Updates

Windows 7 SP1 if you don't have it installed already:

```
sudo cinst -y KB976932
```

Internet Explorer 11, if you actually need it (e.g. **if you use EndNote**):

```bash
sudo cinst -y ie11
```

*(You will need to restart afterwards.)*

## Useful software

Work without going insane:

```bash
sudo cinst -y 7zip.install batterybar git googlechrome irfanview.install irfanviewplugins mactype naps2 netbeans notepadplusplus.install paint.net passwordsafe sourcetree sumatrapdf typora vscode
```

Things not needed if this is a VM inside another desktop OS (e.g. macOS, Linux):

```bash
sudo cinst -y audacity gimp vlc cygwin cyg-get
```

All that juicy cloud + messaging:

```
sudo cinst -y dropbox googledrive onedrive
sudo cinst -y slack skype whatsapp
```

## Encryption

BitLocker doesn't work without a TPM. OK, it does, but you can't set it to unlock with a password, it requires a USB key instead which is impractical for a laptop. So use VeraCrypt instead:

```
sudo cinst -y veracrypt
```

## Other

Reminds to myself to install university software - Office, Nvivo, SPSS, Tableau.

Also Picasa 3.