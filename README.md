### Ansible test

1. Write an Ansible playbook that installs 2 packages named "my_package_1" and "my_package_2" on all the hosts in a group named "my_group".
2. Add error handling to the playbook so it exits with a non-zero status code if the package installation fails on any of the hosts.
3. Modify the playbook to include a task that checks whether the package is already installed on each host, and skips the installation task if it is.
4. Add error handling to the new task so that it exits with a non-zero status code if the package check fails on any of the hosts.
5. Test the playbook with a test inventory that includes both hosts where the package is not installed and hosts where the package is already installed.
Verify that the playbook succeeds on the hosts where the package is installed and fails on the hosts where the package installation fails.


Please refer to [Scenario1](scenario1.txt) and [Scenario2](scenario2.txt) for outputs in both scenarios as required in part 5.

The playbook was tested on Fedora Linux VMs "host1" and "host2" I created for this purpose. For control node, a WSL machine (Ubuntu) was used. 
