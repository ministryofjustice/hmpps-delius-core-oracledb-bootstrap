hmpps-delius-core-oracledb-bootstrap
=========

Role to bootstrap our oracledb amis, run the asm configuration and then create the db schema


Role Variables
--------------

```yaml
    - service_user_name             # defaults to oracle
    - database_global_database_name # db name we are creating
    - database_sid                  #sid of db
    - oradb_sys_password            # defaults to d3l1u5ag41n
    - oradb_system_password         # defaults to d3l1u5ag41n
    - oradb_sysman_password         # defaults to d3l1u5ag41n
    - oradb_dbsnmp_password         # defaults to d3l1u5ag41n
    - oradb_asmsnmp_password        # defaults to d3l1u5ag41n
    - database_characterset         # defaults to AL32UTF8


```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      vars_files:
        - /path/to/vars.yml
      roles:
         - { role: hmpps-delius-core-oracledb-bootstrap }

License
-------

MIT
