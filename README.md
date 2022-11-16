# Emailer-PowerShell

## Summary
PowerShell script that is able to send an email with attachments given a sender
email, recipient email, and SMTP connection information. Allows the user to
customize the email's body and subject.

_Note: If you have any questions or comments you can always use GitHub
discussions, or email me at farinaanthony96@gmail.com._

#### Why
Many scripts generate an output file. These output files usually are in the
form of reports and need to go to a reporting email address or can be sent to
someone's inbox to notify them.

## Requirements
- PowerShell >= v3

## Usage
- Add any additional logic to turn on HTML embedding in the email or to disable
  SMTP credentials.

- Enter the SMTP server information, the sender / recipient information, and
  the email contents into the config.ini file.

- Simply run the script using a PowerShell terminal:

  `./Emailer-PowerShell.ps1`

## Compatibility
This is only tested on Windows and most likely will only work on Windows. It
should be possible to support PowerShell Core on Linux with only minor
adjustments so leave a feature request if there is any interest in that.

## Disclaimer
The code provided in this project is an open source example and should not
be treated as an officially supported product. Use at your own risk. If you
encounter any problems, please log an
[issue](https://github.com/CC-Digital-Innovation/Emailer-PowerShell/issues).

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request ツ

## History
-  version 1.0.1 - 2021/06/08
    - Added support for multiple config files
    - Updated README.md


-  version 1.0.0 - 2021/06/02
    - Initial release

## Credits
Anthony Farina <<farinaanthony96@gmail.com>>

Richard Bocchinfuso <<rbocchinfuso@gmail.com>> for the
[Get-IniFile-Function.ps1](https://github.com/CC-Digital-Innovation/Get-IniFile-Function)
script.
