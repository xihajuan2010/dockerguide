
## login

* 用法


	Usage: docker login [OPTIONS] [SERVER]

	Register or log in to a Docker registry server, if no server is
	specified "https://index.docker.io/v1/" is the default.

    -e, --email=       Email
    --help=false       Print usage
    -p, --password=    Password
    -u, --username=    Username



* 例子


	root@liugang:~# docker login
	Username: username
	Password: ****
	Email: user@domain.com
	Login Succeeded

如果你有一个自己的仓库，你也可以连接到指定主机：

	$ sudo docker login localhost:8080



## logout

* 用法


    Usage: docker logout [OPTIONS] [SERVER]

    Log out from a Docker registry, if no server is
    specified "https://index.docker.io/v1/" is the default.

    --help=false       Print usage



* 例子


	$ sudo docker logout localhost:8080


