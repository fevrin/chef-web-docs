=====================================================
All about |chef|
=====================================================

.. include:: ../../includes_chef/includes_chef_index.rst

Getting Started
=====================================================
**From the beginning:** :doc:`An Overview of Chef </chef_overview>` | :doc:`About Workstations </workstation>` | :doc:`About the Chef Server </chef_server>` | :doc:`About Nodes </nodes>` | :doc:`About Cookbooks </cookbooks>` | :doc:`About Attributes </attributes>` | :doc:`About Resources and Providers </resources>` | :doc:`Custom Resources </custom_resources>` | :doc:`About Knife </knife>` | :doc:`About Chef for Windows </windows>` | :doc:`About Containers </containers>`

**Using Ruby:** :doc:`Chef Style Guide </ruby>`

The Workstation
=====================================================
**The Basics:** :doc:`About the Workstation </workstation>` | :doc:`The chef-repo </chef_repo>` | :doc:`Knife </knife>` | :doc:`Debug Recipes </chef_shell>`

**Install:** :doc:`Install the chef-client on a Workstation </install_dk>` | :doc:`Bootstrap a Node </install_bootstrap>` | :doc:`Create and Sync the chef-repo </chef_repo>`

**Knife:** :doc:`About Knife </knife>` | :doc:`Common Options </knife_common_options>` | :doc:`Working with Knife </knife_using>` --- **Commands:** :doc:`bootstrap </knife_bootstrap>` | :doc:`client </knife_client>` | :doc:`configure </knife_configure>` | :doc:`cookbook </knife_cookbook>` | :doc:`cookbook site </knife_cookbook_site>` | :doc:`data bag </knife_data_bag>` | :doc:`delete </knife_delete>` | :doc:`deps </knife_deps>` | :doc:`diff </knife_diff>` | :doc:`download </knife_download>` | :doc:`edit </knife_edit>` | :doc:`environment </knife_environment>` | :doc:`exec </knife_exec>` | :doc:`list </knife_list>` | :doc:`node </knife_node>` | :doc:`raw </knife_raw>` | :doc:`recipe list </knife_recipe_list>` | :doc:`role </knife_role>` | :doc:`search </knife_search>` | :doc:`serve </knife_serve>` | :doc:`show </knife_show>` | :doc:`ssh </knife_ssh>` | :doc:`ssl check </knife_ssl_check>` | :doc:`ssl fetch </knife_ssl_fetch>` | :doc:`status </knife_status>` | :doc:`tag </knife_tag>` | :doc:`upload </knife_upload>` | :doc:`user </knife_user>` | :doc:`xargs </knife_xargs>`

**Settings:** :doc:`knife.rb </config_rb_knife>` | :doc:`metadata.rb </config_rb_metadata>`

**Tools:** :doc:`chef-shell (executable) </ctl_chef_shell>` | :doc:`chef-apply (executable) </ctl_chef_apply>`

The Workstation
-----------------------------------------------------
The |chef dk| defines a common workflow for cookbook development, including unit and integration testing, identifying lint-like behavior, dedicated tooling, and more:

**Install:** :doc:`Install the chef-dk </install_dk>`

**Components:** :doc:`Kitchen </kitchen>` | :doc:`ChefSpec </chefspec>` | :doc:`Foodcritic </foodcritic>` | :doc:`Berkshelf </berkshelf>` | :doc:`chef-vault </chef_vault>` | :doc:`RuboCop <rubocop>`

**Tools:** :doc:`kitchen (executable) </ctl_kitchen>` | :doc:`chef (executable) </ctl_chef>`

**Settings:** :doc:`kitchen.yml </config_yml_kitchen>`


The Nodes
=====================================================
**The Basics:** :doc:`About Nodes </nodes>` | :doc:`chef-client (agent) </chef_client>` | `The chef-client Run <https://docs.chef.io/chef_client.html#the-chef-client-title-run>`_ | :doc:`Chef Solo </chef_solo>` | :doc:`About the Run-list </run_lists>` | :doc:`Debug Recipes </chef_shell>` | :doc:`Chef for Junos OS </junos>`

**Install:** `About Bootstrap <https://docs.chef.io/chef_client.html#bootstrap-operations>`_ | :doc:`Install the chef-client on a Node (Bootstrap) </install_bootstrap>` and :doc:`knife bootstrap </knife_bootstrap>` | :doc:`Install the chef-client on Windows </install_windows>` | :doc:`Download the chef-client with Omnitruck API </api_omnitruck>`

**Ohai:** :doc:`About Ohai 8 </ohai>` | :doc:`Custom Ohai 8 Plugins </ohai_custom>` | `Ohai 7 <https://docs.chef.io/release/ohai-7/>`_ | `Ohai 6 <https://docs.chef.io/release/ohai-6/>`_

**Settings:** :doc:`client.rb </config_rb_client>` | :doc:`solo.rb </config_rb_solo>`

**Command-line Tools:** :doc:`chef-client (executable) </ctl_chef_client>` | :doc:`chef-shell (executable) </ctl_chef_shell>` | :doc:`chef-solo (executable) </ctl_chef_solo>` | :doc:`ohai (executable) </ctl_ohai>`


Cookbooks
=====================================================
**The basics:** :doc:`About Cookbooks </cookbooks>` | :doc:`About Recipes </recipes>` | :doc:`About Attribute Files </attributes>` |  :doc:`Handlers </handlers>` | `Popular Cookbooks <https://github.com/chef-cookbooks>`_

**Other cokbook components:** :doc:`About Definitions </definitions>` | :doc:`About Files </files>` | :doc:`About Libraries </libraries>` | :doc:`About Cookbook Metadata </cookbook_repo>` | :doc:`About Templates </templates>` | :doc:`About Versions </cookbook_versions>`

**Resources:** :doc:`About Resources </resource>` | :doc:`Common Functionality </resource_common>` --- **Resources:** :doc:`apt_package </resource_apt_package>` | :doc:`apt_update </resource_apt_update>` | :doc:`bash </resource_bash>` | :doc:`batch </resource_batch>` | :doc:`bff_package </resource_bff_package>` | :doc:`breakpoint </resource_breakpoint>` | :doc:`chef_gem </resource_chef_gem>` | :doc:`chef_handler </resource_chef_handler>` | :doc:`chocolatey_package </resource_chocolatey_package>` | :doc:`cookbook_file </resource_cookbook_file>` | :doc:`cron </resource_cron>` | :doc:`csh </resource_csh>` | :doc:`deploy </resource_deploy>` | :doc:`directory </resource_directory>` | :doc:`dpkg_package </resource_dpkg_package>` | :doc:`dsc_resource </resource_dsc_resource>` | :doc:`dsc_script </resource_dsc_script>` | :doc:`easy_install_package </resource_easy_install_package>` | :doc:`env </resource_env>` | :doc:`erlang_call </resource_erlang_call>` | :doc:`execute </resource_execute>` | :doc:`file </resource_file>` | :doc:`freebsd_package </resource_freebsd_package>` | :doc:`gem_package </resource_gem_package>` | :doc:`git </resource_git>` | :doc:`group </resource_group>` | :doc:`homebrew_package </resource_homebrew_package>` | :doc:`http_request </resource_http_request>` | :doc:`ifconfig </resource_ifconfig>` | :doc:`ips_package </resource_ips_package>` | :doc:`ksh </resource_ksh>` | :doc:`launchd </resource_launchd>` | :doc:`link </resource_link>` | :doc:`log </resource_log>` | :doc:`macports_package </resource_macports_package>` | :doc:`mdadm </resource_mdadm>` | :doc:`mount </resource_mount>` | :doc:`ohai </resource_ohai>` | :doc:`openbsd_package </resource_openbsd_package>` | :doc:`osx_profile </resource_osx_profile>` | :doc:`package </resource_package>` | :doc:`pacman_package </resource_pacman_package>` | :doc:`paludis_package </resource_paludis_package>` | :doc:`perl </resource_perl>` | :doc:`portage_package </resource_portage_package>` | :doc:`powershell_script </resource_powershell_script>` | :doc:`python </resource_python>` | :doc:`reboot </resource_reboot>` | :doc:`registry_key </resource_registry_key>` | :doc:`remote_directory </resource_remote_directory>` | :doc:`remote_file </resource_remote_file>` | :doc:`route </resource_route>` | :doc:`rpm_package </resource_rpm_package>` | :doc:`ruby </resource_ruby>` | :doc:`ruby_block </resource_ruby_block>` | :doc:`script </resource_script>` | :doc:`service </resource_service>` | :doc:`smartos_package </resource_smartos_package>` | :doc:`solaris_package </resource_solaris_package>` | :doc:`subversion </resource_subversion>` | :doc:`template </resource_template>` | :doc:`user </resource_user>` | :doc:`windows_package </resource_windows_package>` | :doc:`windows_service </resource_windows_service>` | :doc:`yum_package </resource_yum>` --- **Single Page:** :doc:`Resources and Providers </resources>`

**Custom resources:** :doc:`About Custom Resources </custom_resources>`

**The Recipe DSL:** :doc:`About the Recipe DSL </dsl_recipe>` --- **Methods:** `attribute? <https://docs.chef.io/dsl_recipe.html#attribute>`_ | `cookbook_name <https://docs.chef.io/dsl_recipe.html#cookbook-name>`_ | `control <https://docs.chef.io/dsl_recipe.html#control>`_ | `control_group <https://docs.chef.io/dsl_recipe.html#control-group>`_ | `data_bag <https://docs.chef.io/dsl_recipe.html#data-bag>`_ | `data_bag_item <https://docs.chef.io/dsl_recipe.html#data-bag-item>`_ | `platform? <https://docs.chef.io/dsl_recipe.html#platform>`_ | `platform_family? <https://docs.chef.io/dsl_recipe.html#platform-family>`_ | `reboot_pending <https://docs.chef.io/dsl_recipe.html#reboot-pending>`_ |  `recipe_name <https://docs.chef.io/dsl_recipe.html#recipe-name>`_ | `registry_data_exists? <https://docs.chef.io/dsl_recipe.html#registry-data-exists>`_ | `registry_get_subkeys <https://docs.chef.io/dsl_recipe.html#registry-get-subkeys>`_ | `registry_get_values <https://docs.chef.io/dsl_recipe.html#registry-get-values>`_ | `registry_has_subkeys? <https://docs.chef.io/dsl_recipe.html#registry-has-subkeys>`_ | `registry_key_exists? <https://docs.chef.io/dsl_recipe.html#registry-key-exists>`_ | `registry_value_exists? <https://docs.chef.io/dsl_recipe.html#registry-value-exists>`_ | `resources <https://docs.chef.io/dsl_recipe.html#resources>`_ | `search <https://docs.chef.io/dsl_recipe.html#search>`_ | `shell_out <https://docs.chef.io/dsl_recipe.html#shell-out>`_ | `shell_out! <https://docs.chef.io/dsl_recipe.html#id2>`_ | `shell_out_with_systems_locale <https://docs.chef.io/dsl_recipe.html#shell-out-with-systems-locale>`_ | `tag <https://docs.chef.io/dsl_recipe.html#tag-tagged-untag>`_ | `tagged? <https://docs.chef.io/dsl_recipe.html#tag-tagged-untag>`_ | `untag <https://docs.chef.io/dsl_recipe.html#tag-tagged-untag>`_ | `value_for_platform <https://docs.chef.io/dsl_recipe.html#value-for-platform>`_ | `value_for_platform_family <https://docs.chef.io/dsl_recipe.html#value-for-platform-family>`_ | `Windows Platform Helpers <https://docs.chef.io/dsl_recipe.html#helpers>`_

**Resources for accessing objects in Chef:** :doc:`chef_acl </resource_chef_acl>` | :doc:`chef_client </resource_chef_client>` | :doc:`chef_container </resource_chef_container>` | :doc:`chef_data_bag_item </resource_chef_data_bag_item>` | :doc:`chef_data_bag </resource_chef_data_bag>` | :doc:`chef_environment </resource_chef_environment>` | :doc:`chef_group </resource_chef_group>` | :doc:`chef_mirror </resource_chef_mirror>` | :doc:`chef_node </resource_chef_node>` | :doc:`chef_organization </resource_chef_organization>` | :doc:`chef_role </resource_chef_role>` | :doc:`chef_user </resource_chef_user>` | :doc:`private_key </resource_private_key>` | :doc:`public_key </resource_public_key>`

**Resources for Chef Provisioning:** :doc:`load_balancer </resource_load_balancer>` | :doc:`machine </resource_machine>` | :doc:`machine_batch </resource_machine_batch>` | :doc:`machine_execute </resource_machine_execute>` | :doc:`machine_file </resource_machine_file>` | :doc:`machine_image </resource_machine_image>`

**Community-maintained resources:** `Chef-maintained Cookbooks <https://github.com/chef-cookbooks/>`__ | `Supermarket <https://supermarket.chef.io>`__


The |chef server_title|
=====================================================
.. include:: ../../includes_chef_server/includes_chef_server.rst

**Install Scenarios:** :doc:`Installs </install_server>` | :doc:`Upgrades </upgrade_server>`

**Features:** :doc:`Chef Manage </manage>` | :doc:`Reporting </reporting>` | :doc:`Push Jobs </push_jobs>` | :doc:`Chef Analytics </analytics>` | :doc:`Replication </server_replication>` | :doc:`High Availability </server_high_availability>`

**Manage Server:** :doc:`Runbook </runbook>` (all manage tasks in a single topic) --- **Shorter topics:** :doc:`Backup and Restore </server_backup_restore>` | :doc:`Server Data </server_data>` | :doc:`Firewalls and Ports </server_firewalls_and_ports>` | :doc:`High Availability </server_high_availability>` | :doc:`Logs </server_logs>` | :doc:`Active Directory and LDAP </server_ldap>` | :doc:`Monitor </server_monitor>` | :doc:`Organizations, Groups, and Users </server_orgs>` | :doc:`Replication </server_replication>` | :doc:`Security </server_security>` | :doc:`Services </server_services>` | :doc:`Server Tuning </server_tuning>`

**Chef Manage Webui:** :doc:`Clients </server_manage_clients>` | :doc:`Cookbooks </server_manage_cookbooks>` | :doc:`Data Bags </server_manage_data_bags>` | :doc:`Environments </server_manage_environments>` | :doc:`Nodes </server_manage_nodes>` | :doc:`Reports </server_manage_reports>` | :doc:`Roles </server_manage_roles>`

**Settings and Tools:** :doc:`chef-server.rb </config_rb_server>` | :doc:`chef-server-ctl </ctl_chef_server>` | :doc:`manage.rb </config_rb_manage>` | :doc:`chef-sync.rb </config_rb_chef_sync>` | :doc:`chef-sync-ctl </ctl_chef_sync>` | :doc:`opscode-expander-ctl </ctl_opscode_expander>` | :doc:`opscode-reporting-ctl </ctl_reporting>`

**APIs:** :doc:`Chef Server API </api_chef_server>` | :doc:`Cookbooks Site API </api_cookbooks_site>`

Server Essentials
-----------------------------------------------------
The server acts as a repository for all of the data that may be needed by the |chef client| while it configures a node:

* A :doc:`node object </nodes>` exists for each node that is being managed by the |chef client|
* Each node object consists of a :doc:`run-list </nodes>` and a `collection of attributes <https://docs.chef.io/nodes.html#attributes>`_
* All data that is stored on the |chef server|---including everything uploaded to the server from the |chef repo| and by the |chef client|---is :doc:`searchable </chef_search>` from both recipes (using the `search method <https://docs.chef.io/dsl_recipe.html#search>`_ in the |dsl recipe|) and the workstation (using the :doc:`knife search </knife_search>` subcommand)
* The |chef server| can apply :doc:`global policy settings </policy>` to all nodes across the organization, including for :doc:`data bags </data_bags>`, :doc:`environments </environments>`, and :doc:`roles </roles>`
* The :doc:`authentication </auth_authentication>` process ensures that requests can only be made to the |chef server| by authorized users
* Users, once :doc:`authorized </auth_authorization>` can only perform certain actions
* The |chef server| provides :doc:`powerful search </chef_search>` functionality


Chef Compliance
=====================================================
.. include:: ../../includes_compliance/includes_compliance.rst

**The basics:** :doc:`Overview </compliance>` | :doc:`Install Compliance </install_compliance>` | :doc:`inspec (CLI) </ctl_inspec>`

**InSpec resources:** :doc:`apache_conf </inspec_apache_conf>` | :doc:`apt </inspec_apt>` | :doc:`audit_policy </inspec_audit_policy>` | :doc:`auditd_conf </inspec_auditd_conf>` | :doc:`auditd_rules </inspec_auditd_rules>` | :doc:`bond </inspec_bond>` | :doc:`bridge </inspec_bridge>` | :doc:`command </inspec_command>` | :doc:`csv </inspec_csv>` | :doc:`directory </inspec_directory>` | :doc:`etc_group </inspec_etc_group>` | :doc:`etc_passwd </inspec_etc_passwd>` | :doc:`file </inspec_file>` | :doc:`gem </inspec_gem>` | :doc:`group </inspec_group>` | :doc:`host </inspec_host>` | :doc:`inetd_conf </inspec_inetd_conf>` | :doc:`interface </inspec_interface>` | :doc:`iptables </inspec_iptables>` | :doc:`json </inspec_json>` | :doc:`kernel_module </inspec_kernel_module>` | :doc:`kernel_parameter </inspec_kernel_parameter>` | :doc:`limits_conf </inspec_limits_conf>` | :doc:`login_def </inspec_login_def>` | :doc:`mount </inspec_mount>` | :doc:`mysql_conf </inspec_mysql_conf>` | :doc:`mysql_session </inspec_mysql_session>` | :doc:`npm </inspec_npm>` | :doc:`ntp_conf </inspec_ntp_conf>` | :doc:`oneget </inspec_oneget>` | :doc:`os_env </inspec_os_env>` | :doc:`os </inspec_os>` | :doc:`package </inspec_package>` | :doc:`parse_config_file </inspec_parse_config_file>` | :doc:`parse_config </inspec_parse_config>` | :doc:`pip </inspec_pip>` | :doc:`port </inspec_port>` | :doc:`postgres_conf </inspec_postgres_conf>` | :doc:`postgres_session </inspec_postgres_session>` | :doc:`process </inspec_process>` | :doc:`registry_key </inspec_registry_key>` | :doc:`script </inspec_script>` | :doc:`security_policy </inspec_security_policy>` | :doc:`service </inspec_service>` | :doc:`ssh_config </inspec_ssh_config>` | :doc:`sshd_config </inspec_sshd_config>` | :doc:`user </inspec_user>` | :doc:`windows_feature </inspec_windows_feature>` | :doc:`yaml </inspec_yaml>` | :doc:`yum </inspec_yum>` --- **Single Page:** :doc:`InSpec Reference </inspec_reference>`




.. Hide the TOC from this file.

.. toctree::
   :hidden:

   actions
   analytics
   analytics_monitor
   analytics_rules
   analytics_webui_tasks
   api_analytics
   api_chef_server
   api_compliance
   api_cookbooks_site
   api_omnitruck
   api_push_jobs
   api_reporting
   attributes
   auth
   auth_authentication
   auth_authorization
   aws_marketplace
   azure_portal
   berkshelf
   chef_client
   chef_client_security
   chef_cookbooks
   chef_dk
   chef_overview
   chef_private_keys
   chef_quick_overview
   chef_repo
   chef_search
   chef_server
   chef_shell
   chef_solo
   chef_system_requirements
   chef_vault
   chefspec
   community
   community_contributions
   community_guidelines
   compliance
   config_json_delivery
   config_rb
   config_rb_analytics
   config_rb_chef_sync
   config_rb_client
   config_rb_compliance
   config_rb_delivery_optional_settings
   config_rb_knife
   config_rb_knife_optional_settings
   config_rb_manage
   config_rb_metadata
   config_rb_metadata
   config_rb_policyfile
   config_rb_push_jobs_server
   config_rb_reporting
   config_rb_server
   config_rb_server_optional_settings
   config_rb_solo
   config_rb_supermarket
   config_yml_kitchen
   containers
   cookbook_repo
   cookbook_versions
   cookbooks
   ctl_analytics
   ctl_chef
   ctl_chef_apply
   ctl_chef_backend
   ctl_chef_client
   ctl_chef_init
   ctl_chef_server
   ctl_chef_shell
   ctl_chef_solo
   ctl_chef_sync
   ctl_delivery
   ctl_delivery_server
   ctl_inspec
   ctl_kitchen
   ctl_manage
   ctl_ohai
   ctl_opscode_expander
   ctl_push_jobs_client
   ctl_reporting
   ctl_supermarket
   custom_resources
   data_bags
   debug
   definitions
   delivery
   delivery_pipeline
   delivery_build_cookbook
   delivery_manage_dependencies
   delivery_manage_secrets
   delivery_server_tuning
   delivery_truck
   delivery_users_and_roles
   dsl_compliance
   dsl_custom_resource
   dsl_delivery
   dsl_handler
   dsl_recipe
   environment_variables
   environments
   errors
   error_messages
   feedback
   files
   foodcritic
   glossary
   handlers
   inspec_reference
   inspec_apache_conf
   inspec_apt
   inspec_audit_policy
   inspec_auditd_conf
   inspec_auditd_rules
   inspec_bond
   inspec_bridge
   inspec_command
   inspec_csv
   inspec_directory
   inspec_etc_group
   inspec_etc_passwd
   inspec_file
   inspec_gem
   inspec_group
   inspec_host
   inspec_inetd_conf
   inspec_interface
   inspec_iptables
   inspec_json
   inspec_kernel_module
   inspec_kernel_parameter
   inspec_limits_conf
   inspec_login_def
   inspec_mount
   inspec_mysql_conf
   inspec_mysql_session
   inspec_npm
   inspec_ntp_conf
   inspec_oneget
   inspec_os_env
   inspec_os
   inspec_package
   inspec_parse_config_file
   inspec_parse_config
   inspec_pip
   inspec_port
   inspec_postgres_conf
   inspec_postgres_session
   inspec_process
   inspec_registry_key
   inspec_script
   inspec_security_policy
   inspec_service
   inspec_ssh_config
   inspec_sshd_config
   inspec_user
   inspec_windows_feature
   inspec_yaml
   inspec_yum
   install
   install_analytics
   install_bootstrap
   install_compliance
   install_delivery
   install_delivery_aws
   install_delivery_ssh
   install_dk
   install_omnibus
   install_push_jobs
   install_reporting
   install_server
   install_server_ha
   install_server_ha_aws
   install_server_ha_drbd
   install_server_post
   install_server_pre
   install_server_tiered
   install_windows
   integrate_compliance_chef_server
   integrate_delivery_bitbucket
   integrate_delivery_github
   integrate_delivery_ldap
   junos
   kitchen
   knife
   knife_common_options
   knife_bootstrap
   knife_client
   knife_configure
   knife_cookbook
   knife_cookbook_site
   knife_data_bag
   knife_delete
   knife_deps
   knife_diff
   knife_download
   knife_edit
   knife_environment
   knife_exec
   knife_list
   knife_node
   knife_raw
   knife_recipe_list
   knife_role
   knife_search
   knife_serve
   knife_show
   knife_ssh
   knife_ssl_check
   knife_ssl_fetch
   knife_status
   knife_tag
   knife_upload
   knife_user
   knife_using
   knife_xargs
   libraries
   manage
   nodes
   ohai
   ohai_custom
   openstack
   packages
   page_not_found
   plugin_community
   plugin_kitchen_vagrant
   plugin_knife
   plugin_knife_analytics
   plugin_knife_authenticated_requests
   plugin_knife_azure
   plugin_knife_bluebox
   plugin_knife_bluelock
   plugin_knife_custom
   plugin_knife_ec2
   plugin_knife_eucalyptus
   plugin_knife_google
   plugin_knife_hp
   plugin_knife_linode
   plugin_knife_openstack
   plugin_knife_push_jobs
   plugin_knife_rackspace
   plugin_knife_reporting
   plugin_knife_supermarket
   plugin_knife_terremark
   plugin_knife_vcloud
   plugin_knife_windows
   policy
   policyfile
   proxies
   provisioning
   push_jobs
   quick_start
   recipes
   reporting
   release_notes
   releases
   resource
   resource_apt_package
   resource_apt_update
   resource_bash
   resource_batch
   resource_bff_package
   resource_breakpoint
   resource_chef_acl
   resource_chef_client
   resource_chef_container
   resource_chef_data_bag
   resource_chef_data_bag_item
   resource_chef_environment
   resource_chef_gem
   resource_chef_group
   resource_chef_handler
   resource_chef_mirror
   resource_chef_node
   resource_chef_organization
   resource_chef_role
   resource_chef_user
   resource_chocolatey_package
   resource_common
   resource_cookbook_file
   resource_cron
   resource_csh
   resource_deploy
   resource_directory
   resource_dpkg_package
   resource_dsc_resource
   resource_dsc_script
   resource_easy_install_package
   resource_env
   resource_erlang_call
   resource_examples
   resource_execute
   resource_file
   resource_freebsd_package
   resource_gem_package
   resource_git
   resource_group
   resource_homebrew_package
   resource_http_request
   resource_ifconfig
   resource_ips_package
   resource_ksh
   resource_launchd
   resource_link
   resource_load_balancer
   resource_log
   resource_machine
   resource_machine_batch
   resource_machine_execute
   resource_machine_file
   resource_machine_image
   resource_macports_package
   resource_mdadm
   resource_mount
   resource_ohai
   resource_openbsd_package
   resource_osx_profile
   resource_package
   resource_pacman_package
   resource_paludis_package
   resource_perl
   resource_portage_package
   resource_powershell_script
   resource_private_key
   resource_public_key
   resource_python
   resource_reboot
   resource_registry_key
   resource_remote_directory
   resource_remote_file
   resource_route
   resource_rpm_package
   resource_ruby
   resource_ruby_block
   resource_script
   resource_service
   resource_smartos_package
   resource_solaris_package
   resource_subversion
   resource_template
   resource_user
   resource_windows_package
   resource_windows_service
   resource_yum
   resources
   roles
   rubocop
   ruby
   run_lists
   runbook
   secrets
   security_notes
   server_backup_restore
   server_components
   server_data
   server_firewalls_and_ports
   server_high_availability
   server_ldap
   server_logs
   server_manage_clients
   server_manage_cookbooks
   server_manage_data_bags
   server_manage_environments
   server_manage_nodes
   server_manage_reports
   server_manage_roles
   server_monitor
   server_orgs
   server_replication
   server_security
   server_services
   server_tuning
   server_users
   server_webui_tasks
   simple_walkthrough
   slides
   style_guide
   supermarket
   supported_platforms
   templates
   uninstall
   upgrade_analytics
   upgrade_client
   upgrade_client_notes
   upgrade_compliance
   upgrade_server
   upgrade_server_notes
   upgrade_server_open_source_notes
   verify_packages
   windows
   workstation
