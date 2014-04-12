nsuniq
======

none sorted unique util to replace "sort | uniq"

OPTIONS:
* -c:  like "sort | uniq -c"
* -kN : like "awk '{print $N;}' | sort | uniq"
* -F'SEP' : like "awk -F'SEP' '{print $N;}' | sort | uniq"
 
Implemented by Shell and awk, watch the source code for the detail
