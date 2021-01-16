# ansible_role
Introduction:
ansible roles come in ansible for the managment of our code when it becomes large. With ansible role we can separate our code in the variables, tasks and more.
For the intro ansible roles we are going to setup load balancer with roles.
We will have two roles as myapache and myloadbalancer.
myapache is the for the apache webserver httpd configuration in the backend servers.
myloadbalancer is for the front-end server.
____myapache_role___
ansible-galaxy init myapache (will create myapache role)
for myapache role i am adding apache_main.yml in this repo for main.yml of tasks folder inside myapache role.
____myapache_role___
ansible-galaxy init myloadbalancer (will create myapache role)
for myloadbalancer role i am adding loadbalancer_main.yml in this repo for main.yml of tasks folder inside myloadbalancer role.
____main.yml____
this will be our playbook to setup loadbalancer.
