START Detached:	docker-compose -p rt up -d
STOP: 	docker-compose -p rt down
START Undetached: docker-compose -p rt up -d


.:
total 4
drwx------. 4 root root  74 Sep 15 17:56 .
drwxr-xr-x. 5 root root  67 Sep 15 14:57 ..
-rw-------. 1 root root 468 Sep 15 16:56 docker-compose.yml
drwx------. 3 root root 117 Sep 15 18:51 nginx
-rw-------. 1 root root   0 Sep 15 18:53 README.md
drwxr-xr-x. 2 root root  24 Sep 15 15:16 site

./nginx:
total 16
drwx------. 3 root root  117 Sep 15 18:51 .
drwx------. 4 root root   74 Sep 15 17:56 ..
drwx------. 2 root root   51 Sep 15 18:52 conf.d
-rw-r--r--. 1 root root  643 Sep  6 00:53 nginx.conf
-rw-------. 1 root root  538 Sep 15 16:17 nginx.conf.orig
-rw-------. 1 root root 1326 Sep 15 13:31 nginx-selfsigned.crt
-rw-------. 1 root root 1704 Sep 15 13:31 nginx-selfsigned.key

./nginx/conf.d:
total 8
drwx------. 2 root root   51 Sep 15 18:52 .
drwx------. 3 root root  117 Sep 15 18:51 ..
-rw-r--r--. 1 root root 1706 Sep 15 18:45 default.conf
-rw-r--r--. 1 root root 1093 Aug 11 14:50 default.conf.orig

./site:
total 4
drwxr-xr-x. 2 root root 24 Sep 15 15:16 .
drwx------. 4 root root 74 Sep 15 17:56 ..
-rwxr-xr-x. 1 root root 88 Sep 15 14:39 index.html
