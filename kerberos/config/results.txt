## Node 1

### admin
[root@ip-172-31-50-202 ~]# kinit admin@VINKOS.COM
Password for admin@VINKOS.COM: 
[root@ip-172-31-50-202 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: admin@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:04:17  12/04/2018 15:04:17  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:04:17
	Addresses: (none)


### user1
[root@ip-172-31-50-202 ~]# kinit user1@VINKOS.COM
Password for user1@VINKOS.COM: 
[root@ip-172-31-50-202 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user1@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:04:29  12/04/2018 15:04:29  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:04:29
	Addresses: (none)


### user2	
[root@ip-172-31-50-202 ~]# kinit user2@VINKOS.COM
Password for user2@VINKOS.COM: 
[root@ip-172-31-50-202 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user2@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:04:42  12/04/2018 15:04:42  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:04:42
	Addresses: (none)

### user3	
[root@ip-172-31-50-202 ~]# kinit user3@VINKOS.COM
Password for user3@VINKOS.COM: 
[root@ip-172-31-50-202 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user3@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:04:53  12/04/2018 15:04:53  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:04:53
	Addresses: (none)

### user4	
[root@ip-172-31-50-202 ~]# kinit user4@VINKOS.COM
Password for user4@VINKOS.COM: 
[root@ip-172-31-50-202 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user4@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:05:15  12/04/2018 15:05:15  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:05:15
	Addresses: (none)
[root@ip-172-31-50-202 ~]# 



## Node 2

### admin
[root@ip-172-31-60-113 ~]# kinit admin@VINKOS.COM
Password for admin@VINKOS.COM: 
[root@ip-172-31-60-113 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: admin@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:08:13  12/04/2018 15:08:13  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:08:13
	Addresses: (none)

### user1
[root@ip-172-31-60-113 ~]# kinit user1@VINKOS.COM
Password for user1@VINKOS.COM: 
[root@ip-172-31-60-113 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user1@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:09:00  12/04/2018 15:09:00  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:09:00
	Addresses: (none)

### user2	
[root@ip-172-31-60-113 ~]# kinit user2@VINKOS.COM
Password for user2@VINKOS.COM: 
[root@ip-172-31-60-113 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user2@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:09:09  12/04/2018 15:09:09  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:09:09
	Addresses: (none)

### user3
[root@ip-172-31-60-113 ~]# kinit user3@VINKOS.COM
Password for user3@VINKOS.COM: 
kinit: Password incorrect while getting initial credentials
[root@ip-172-31-60-113 ~]# kinit user3@VINKOS.COM
Password for user3@VINKOS.COM: 
[root@ip-172-31-60-113 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user3@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:09:26  12/04/2018 15:09:26  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:09:26
	Addresses: (none)

### user4
[root@ip-172-31-60-113 ~]# kinit user4@VINKOS.COM
Password for user4@VINKOS.COM: 
[root@ip-172-31-60-113 ~]# klist -a
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: user4@VINKOS.COM

Valid starting       Expires              Service principal
12/03/2018 15:09:36  12/04/2018 15:09:36  krbtgt/VINKOS.COM@VINKOS.COM
	renew until 12/10/2018 15:09:36
	Addresses: (none)

