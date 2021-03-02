<a href="https://www.uniqconsulting.ch"><img src="https://www.uniqconsulting.ch/fileadmin/images/logo-main.png" alt="uniQconsulting" width="250px"/></a>

# ansible.uniqlog


This Ansible Role install, configure and update a Linux Graylog server. The following tasks will be configured:
* `Install and configure MongoDB`
* `Install and configure Java`
* `Install and configure Graylog`

Installation with One-Line-setup:

``` bash
curl https://raw.githubusercontent.com/uniQconsulting-ag/ansible.uniqlog/master/setup.sh | sh
```

Installation with ansible-galaxy:

``` bash
ansible-galaxy install uniqconsulting.uniqlog
```

## Requirements

* Currently only tested with RHEL 8
* Ansible 2.9 or higher is required for this Ansible Role

## Dependencies

This Ansilbe Role uses:
- uniqconsulting.os_basic
- uniqconsulting.firewall
- uniqconsulting.open_vm_tools
- uniqconsulting.elasticsearch
- uniqconsulting.mongodb
- uniqconsulting.nginx
- uniqconsulting.graylog

# uniQconsulting ag

uniQconsulting ag is an IT consulting company with headquarters in Bassersdorf, Switzerland and a wholly owned subsidiary of Netcloud AG since 2017.
Netcloud is a privately held company, reputed for Network and Cloud Services in Switzerland. Although operating independently, both companies have a long history of close collaboration.

uniQconsulting provides a wide range of IT services from the datacenter to the edge and the cloud. The services and solutions of uniQconsulting are well established among clients in business areas like financial services, health care, the public sector and medium sized enterprises.

Depending on individual client requirements, uniQconsulting can assume responsibility for selected, or for all phases of a project. Highly certified and experienced staff guarantee successful implementations. Projects are monitored from start to finish. 

Once a project has been successfully completed, comprehensive services are available to the customer. Our trilingual Expert Helpdesk, based in Switzerland, can take on specific tasks, offloading the client staff, or proactively monitor the IT infrastructure, responding appropriately in the event of an incident or pending change. This gives customers the certainty of being able to call on the appropriate specialist if necessary, without having to build up this know-how internally.

By outsourcing services related to the IT infrastructure, customers can focus on business-applications and processes, resulting in greater transparency and financial predictability in IT operations. The experts at uniQconsulting help customers to create a long-term IT strategy, supporting their overall business goals.

Compliance and security topics are becoming increasingly complex and expensive. Not shying away from thinking outside the box, uniQconsulting focusses on designing high quality and game-changing IT Solutions, with the specific goal of optimizing efficiency and security in digital workflows while maximizing ROI.

We believe in IT-driven success.

License
-------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Mike Gubser <mgubser@uniqconsulting.ch>
