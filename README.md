# SecurityCLITool
Description of how I use the Security CLI Tool 

## To make a new Keychain
`security create-keychain <keychain_name>.<extension>`

## To add a new password
    security add-generic-Password -s service_name -a account_name -w password

## To find a password by service
`security find-generic-Password -s service_name 

## To find a password by service
`security find-generic-Password -a account_name 

