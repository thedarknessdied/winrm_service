# winrm_service

## Description:
  This is a secondary development project based on Pywinrm, which applies Winrm service communication implemented by Pywinrm. This project aims to achieve persistent control of the target host through the WinRM service enabled on Windows (Win7 and above automatically install WinRM service, Windows Server 2012 and above automatically start WinRM service, and other versions require manual service startup), and is written as a tool for WinRM service post penetration attacks. It is an attack script that integrates horizontal penetration, permission location, and vertical penetration in post penetration attacks.

## History:
  [+] On August 22, 2023, the current project only presents a demonstration test file (currently only in command line format, which will be considered as a GUI interface in the future). Currently, it simply implements the functions of file upload and download, as well as powershell rebound sessions

## Usage:
  upload_file(src_address: str, destination: str, chunk_size: int = 1024)
    Upload 
      files src_address Upload file address with
      destination Destination address for uploading files
      chunk_size File read block size
      
  download_file(src_address: str, destination: str)    
    Download files
      files src_address Download file address with
      destination Destination address for Download files
      
  get_shell(host: str, port: int)
    Bounce shell
  
  run_cmd(command, args=())
    Execute cmd command
    
  run_ps(script)
    Execute powershell commands
    
## Reference/Reference:
  [+] https://github.com/diyan/pywinrm
