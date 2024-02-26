## Role - rol-capg-openalert_DB_Sync_Postgresql

Role used to Openalert DB Sync Postgresql Unix

## Requirements

Requires postgresql account , ID_INSTANCE_DB and target server name.

## Role Variables
postgre_account: Provide postgresql account Name while running playbook.
ID_INSTANCE_DB: Provide Instance id while running playbook.

## Usage

Run the playbook using the command:
ansible-playbook openalert.yml 

## Dependencies

Splunk Server

## Example Playbook

    - hosts: all
      gather_facts: false
      roles:
        - rol-capg-openalert_DB_Sync_Postgresql

## License

CAPGEMINI CIS

## Author Information

PU Automation.


