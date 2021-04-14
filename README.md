# ansible_implementation_grading
Clone repo for grading scripts
## Before starting need to run these two commands 
* export GUID=`hostname | awk -F"." '{print $2}'`
* ansible-playbook lab-2-grade.yml -e GUID=${GUID}
