# Detailed Guide on Installing and Configuring MySQL Database

First, download the MySQL installation package.

After downloading, double-click the `.msi` file to open it, and you’ll see the following screen:

![choosing-a-setup-type](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/choosing-a-setup-tyep.png)

 - Annotation 1: Install all products required for the MySQL database;
 - Annotation 2: Use only the MySQL database server;
 - Annotation 3: Use only the MySQL database client;
 - Annotation 4: Install all products, including the MySQL database;
 - Annotation 5: Manually select the MySQL products to install.

Here, we only need to select **Annotation 2** for `Server only`, then click `Next` to proceed to the following screen:

![installation](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/installation.png)

As shown above, this is the installation prompt screen. Simply click `Execute`.

![installation-2](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/installation-2.png)

 - Annotation 1: Shows the current status;
 - Annotation 2: Shows the progress of the installation;
 - Annotation 3: Displays or hides upgrade information.

Once the installation progress reaches `100%`, you’ll see the following:

![installation-3](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/installation-3.png)

This indicates that the MySQL installation is complete. Click `Next`.

![product-configuration](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/product-configuration.png)

As shown above, it’s time to configure the product settings. Click `Next` to continue.

![type-and-networking](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/type-and-networing.png)

 - Annotation 1: Configure the server type;
 - Annotation 2: Select the `TCP/IP` protocol;
 - Annotation 3: Choose the port number `3306`.

Use the default settings and click `Next`.

![accounts-and-roles](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/accounts-and-roles.png)

This screen is for setting accounts and roles. Here, you only need to set the password for the `root` account (make sure to remember this password, as it’s required for logging into MySQL). The password must be at least four characters. Once set, click `Next`.

![windows-service](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/windows-service.png)

 - Annotation 1: Since we are using `mysql-5.7.17`, the default server name is `MySQL57`;
 - Annotation 2: Default to `Standard System Account`.

Keep the default settings and click `Next`.

![plugins-and-extensions](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/plugins-and-extensions.png)

For `Plugins and Extension` configuration, you can skip this step and click `Next`.

![apply-server-configuration](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/apply-server-configuration.png)

This screen is for confirming the server configuration settings. After verification, click `Execute`.

![apply-server-configuration-2](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/apply-server-configuration-2.png)

Server configuration is in progress. If a security warning appears on your computer, allow it by clicking "Agree."

![apply-server-configuration-3](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/apply-server-configuration-3.png)

When the server configuration is complete, click `Finish`.

![product-configuration-next](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/product-configuration-next.png)

This screen further confirms the configuration is complete. Click `Next`.

![installation-complete](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/installation-complete.png)

At this point, the MySQL installation is complete. Click `Finish`. To check MySQL’s installation, open the MySQL command line tool and verify as shown below:

![mysql-client](https://github.com/guobinhit/mysql-tutorial/blob/master/images/install-mysql/mysql-client.png)

As shown, the installation was successful!

----------

**Note**: In this guide, we only installed the MySQL server. For client tools, `Navicat for MySQL` and `DbVisualizer` are recommended.

----------
———— ☆☆☆ —— [Back to the Simplest MySQL Tutorial](https://github.com/guobinhit/mysql-tutorial/blob/master/README.md) —— ☆☆☆ ————
