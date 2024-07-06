create a new repo using 

repo location => # cd /etc/yum.repos.d/

# vim rheliso.repo and paste repos code.
"""
[path-1]
name=This is my local repo baseOS dir
baseurl=file:////shiv/BaseOS
enabled=1
gpgcheck=0
"""
[path-2]
name=This is my local repo appstram dir
baseurl=file:////shiv/AppStream
enabled=1
gpgcheck=0
