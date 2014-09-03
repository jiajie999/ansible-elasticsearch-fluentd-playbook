ansible-elasticsearch-fluentd-playbook
======================================



Intro
-----
 A simple playbook use to set up elasticsearch and fluentd cluster. 
 After install, you can get a fluentd cluster which pass logs to mongo and elasticsearch.


How to use:

    git clone git@github.com:jiajie999/ansible-elasticsearch-fluentd-playbook.git
    
    vi site.yml
    
        Change hosts
    
    vi td-agent/templates and td-agent-master/templates
    
        Add your config
    
    ansible-playbook site.yml -k
    
        Enter your password
    
    Hope all is well :)
    
    

