# SecurityCLITool
Description of how I use the Security CLI Tool.<br>
The security tools docs are mentioned here.[Documentation](https://ss64.com/osx/security.html)<br>
The tool is native as far as I understand to MacOs.


## To make a new Keychain
    security create-keychain <keychain_name>.<extension>`

## To add a new password
    security add-generic-Password -s service_name -a account_name -w password

## To find a password by service
    security find-generic-Password -s service_name 

## To find a password by acct
    security find-generic-Password -a account_name 

