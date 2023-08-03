Shell basics readme
0-current_working_directory:
 #!/bin/bash
 pwd
100-lets_move: 
 #!/bin/bash
 mv [[:upper:]]* /tmp/u
101-clean_emacs:    
 #!/bin/bash
 rm *~
102-tree:               
 #!/bin/bash
 mkdir -p welcome/to/school
103-commas:                 
 #!/bin/bash
 ls -amvp
10-back:
 #!/bin/bash
 cd -               
11-lists:                    
 #!/bin/bash
 ls . .. /boot -la
12-file_type:
 #!/bin/bash
 file /tmp/iamafile
13-symbolic_link:
 #!/bin/bash
 ln -sf /bin/ls __ls__
14-copy_html:
 #!/bin/bash
 cp *.html ../
1-listit:
 #!/bin/bash
 ls
2-bring_me_home:          
 #!/bin/bash
 cd ~
3-listfiles:         
 #!/bin/bash
 ls -l
4-listmorefiles:        
  #!/bin/bash
 ls -al
5-listfilesdigitonly:
  #!/bin/bash
 ls -lan
6-firstdirectory:
 #!/bin/bash
 mkdir /tmp/my_first_directory
7-movethatfile:
 #!/bin/bash
 mv /tmp/betty /tmp/my_first_directory
8-firstdelete: 
 #!/bin/bash
 rm /tmp/my_first_directory/betty
9-firstdirdeletion:       
 #!/bin/bash
 rm -r /tmp/my_first_directory
school.mgc:
 0 string SCHOOL School data
!:mime School
