# winrm_service

Description
  A secondary development project based on Pywinrm, currently only a demo test file, which applies the Winrm service communication implemented by Pywinrm and simply implements the functions of uploading, downloading files, and hosting rebound sessions

Usage:
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
    
Reference/Reference
  [+] https://github.com/diyan/pywinrm
