# linux Managing users and groups

Create users test1, test2, and admin. 
	useradd test1
	useradd test2
	useradd admin

Create a group named helpdesk and add the newly created users to the group.
	groupadd helpdesk
	groupadd -G helpdesk test1 test2 admin 


