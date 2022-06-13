# SecurityCLITool
Description of how I use the Security CLI Tool.<br>
The security tools docs are mentioned here [Documentation](https://ss64.com/osx/security.html)<br>
The tool is native as far as I understand to MacOs.


## To list all keychains
    security list-keychains

## To make a new Keychain
    security create-keychain <keychain_name>.<extension>`

## To add a new password
    security add-generic-password -s service_name -a account_name -w password <keychain_name>.<extension>`

## To find a password by service
    security find-generic-password -s service_name 

## To find a password by acct
    security find-generic-password -a account_name 

