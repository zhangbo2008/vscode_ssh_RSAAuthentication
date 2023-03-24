# vscode_ssh_RSAAuthentication

vscode ssh免密:
	Host 119.29xxxxxx
	  HostName 119.29xxxxxx
	  Port 22
	  User root
	  PreferredAuthentications publickey
	  IdentityFile C:\Users\Administrator\.ssh\id_rsa
	C:\Users\Administrator\.ssh  里面存了 id_rsa.pub
		发送给linux服务器的/root/.ssh  然后 cd /root/.ssh
		 cat id_rsa.pub >> authorized_keys
	这两个配上即可.
	这两个配上即可.
