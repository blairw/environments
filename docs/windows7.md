# Windows 7

Windows 7 is still supported until 14th January 2020 so might as well make good use of it for the next (as of time of writing) year and a half!

## Chocolatey

As admin, to make everything else easier:

```
cinst -y sudo
```

Windows 7 SP1 if you don't have it installed already:

```
sudo cinst -y KB976932
```

Work without going insane - multimedia, docs, dev, admin:

```
sudo cinst -y audacity gimp paint.net vlc
sudo cinst -y googlechrome naps2 passwordsafe sumatrapdf typora
sudo cinst -y cygwin cyg-get git netbeans notepadplusplus sourcetree vscode
sudo cinst -y batterybar conemu mactype processhacker
```

BitLocker doesn't work without a TPM. OK, it does, but you can't set it to unlock with a password, it requires a USB key instead which is impractical for a laptop. So use VeraCrypt instead:

```
sudo cinst -y veracrypt
```

All that juicy cloud + messaging:

```
sudo cinst -y dropbox googledrive onedrive
sudo cinst -y slack skype whatsapp
```

## Other

I personally install Nvivo and SPSS provided by my university.

My university also provides Office 365:

```
sudo cinst -y office365proplus
```

Picasa 3.