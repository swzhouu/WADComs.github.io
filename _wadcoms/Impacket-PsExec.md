---
description: |
  Impacket's psexec.py offers psexec like functionality. This will give you an interactive shell on the Windows host.

  Command Reference:

  	Target IP: 10.10.10.1
  
  	Domain: test.local

  	Username: john

  	Password: password123
functions:
  Password:
    - code: |
        python3 psexec.py test.local/john:password123@10.10.10.1
  Username:
    - code: |
        empty
  SMB:
    - code: |
        empty
---