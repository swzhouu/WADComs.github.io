---
description: |
  Impacket's wmiexec.py uses the Windows Management Instrumentation (WMI) to give you an interactive shell on the Windows host.

  Command Reference:

  	Target IP: 10.10.10.1
  
  	Domain: test.local

  	Username: john

  	Password: password123
functions:
  Password:
    - code: |
        python3 wmiexec.py test.local/john:password123@10.10.10.1
  Username:
    - code: |
        empty
  WMI:
    - code: |
        empty
---