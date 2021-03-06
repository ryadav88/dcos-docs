---
post_title: Adding Users Manually
menu_order: 4
---

You can add users to your DC/OS cluster from a terminal by using the `dcos_add_user.py` script.

**Prerequisites:**

- DC/OS is [installed](/docs/1.8/administration/installing/)

1.  [SSH](/docs/1.8/administration/access-node/sshcluster/) to a master node and run this command, where `<email>` is the user's email:

    ```bash
    $ sudo -i /opt/mesosphere/bin/dcos_add_user.py <email>
    ```
    
1.  Send the URL of your DC/OS cluster (e.g. `http://<public-master-ip>/`) to the new user. The user specified by `<email>` can now login and access the cluster.




