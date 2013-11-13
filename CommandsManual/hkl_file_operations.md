#HKL file Operations

TWOCOLUMNS

[INC ../commands/hklstat]
[INC ../commands/omit]
[INC ../commands/hkledit]
[INC ../commands/hklexclude]
[INC ../commands/hklappend]
[INC ../commands/hklview]

NOCOLUMNS

>OLEX2 For more advanced HKL processing, a Python script may be used. A sample hklf5.py script is provided in {Olex2 folder}/etc/scripts. The script can be copied and modified to accommodate any particular twinning law and run inside Olex2. The script allows creating an HKLF 5 file where reflections which belong to different twin components are assigned different batch numbers. To run a python script in Olex2 use the following command to load the script:
>>@py -l
This command shows a 'File Open' dialog, a python script can be selected. After loading the script can be modified and executed by pressing OK.
