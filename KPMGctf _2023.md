## LOCAL FILE INCLUSION    
`Web Security`

An attacker can use Local File Inclusion (LFI) to trick the web application into exposing or running files on the web server. An LFI attack may lead to information disclosure, remote code execution, or even Cross-site Scripting (XSS). Typically, LFI occurs when an application uses the path to a file as input. If the application treats this input as trusted, a local file may be used in the include statement.

In KPMG CTF2023 came through this web challenge where the 'secret' GET param is shown in page soruce and the path to the flag is mentioned, 
using the information `?secret=../../../config/iamsecure.txt`

[Resources](https://d00mfist.gitbooks.io/ctf/content/remote_file_inclusion.html)
***
## OTP BYPASSING
 `Network Security`

The OTP used here is auto generated with a TOTP which generates a OTP for every 30 seconds.Got the TOTP from the sqlconfig file in the FTP port on which anonymus login is allowed.

[OTP GENERATOR](https://totp.app/)
