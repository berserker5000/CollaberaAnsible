##MACADDRESS company retrieving

To use this ansible script please make sure you have ansible installed on your computer (https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

The main command you need to use is:

`ansible-playbook -i '127.0.0.1,' task.yml -e "MACADDRESS=14:7d:da:e0:23:e8"`

You can specify any macaddress you want. Also if you have an API key from the site https://macaddress.io/ you can specify it by adding variable API_KEY
(example: `ansible-playbook -i '127.0.0.1,' task.yml -e "MACADDRESS=14:7d:da:e0:23:e8 API_KEY=at_SomEKEyHereTOprovide" `)

But if you don't have it, there are a key and a macaddress just for tests. API key can handle only 100 requests per day. 