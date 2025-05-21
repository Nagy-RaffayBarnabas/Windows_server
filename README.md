# Windows_server
Windows_server

user create
 dsadd user "cn=user1,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi" -samid user1
dsadd user "cn=user1,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi" -samid user1 -pwd Pass1234%


 group create
 dsadd group "cn=aaa,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi" -members "cn=user1,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi"
dsadd group "cn=aaa,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi" -members "cn=user1,ou=gyártás,ou=mérnökség,dc=minta,dc=helyi" -secgrp yes -scope g

\\WIN-EGJ3HKAV6HK\Sajat\%username%


service install : *TFTP*
dism /online /enable-feature /featurename:TFTP /all
HypervisorPlatform
TelnetClient
IIS-WebServerRole

dism /online /get-features
