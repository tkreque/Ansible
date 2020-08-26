# Ansible scripts
This Ansible scripts are used for installation of a Lab but can be used for administration with few changes.

###### Requirements
- Ansible 2.9.12
- Python 3.8.2
- pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8)

## Folder tree
```
.
├── configs
│   └── inventory.yml
├── README.md
├── roles
│   ├── apache
│   │   └── tasks
│   │       ├── main.yml
│   │       └── RedHat
│   │           └── apache.yml
│   ├── general
│   │   ├── tasks
│   │   │   ├── main.yml
│   │   │   └── RedHat
│   │   │       ├── ntp.yml
│   │   │       ├── osdependencies.yml
│   │   │       ├── ostools.yml
│   │   │       └── selinux.yml
│   │   ├── templates
│   │   │   └── ntp.conf.j2
│   │   └── vars
│   │       └── main.yml
│   ├── mysql
│   │   ├── tasks
│   │   │   ├── main.yml
│   │   │   └── RedHat
│   │   │       └── mysql.yml
│   │   └── vars
│   │       └── main.yml
│   ├── php
│   │   └── tasks
│   │       ├── main.yml
│   │       └── RedHat
│   │           └── php.yml
│   └── wordpress
│       ├── tasks
│       │   ├── main.yml
│       │   ├── mysql.yml
│       │   └── RedHat
│       │       └── wordpress.yml
│       ├── templates
│       │   └── wp-config.php.j2
│       └── vars
│           └── main.yml
└── wordpress.yml

22 directories, 22 files
```

## Scripts

