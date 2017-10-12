# rootssetup
Roots.io setup of Trellis/Bedrock/Sage

1.  `mkdir <dirname> && cd <dirname>`
2.  `git clone --depth=1 https://github.com/roots/trellis.git && rm -rf trellis/.git`
3.  `git clone --depth=1 https://github.com/roots/bedrock.git site && rm -rf site/.git`
4.  `code .`
5.  trellis/group_vars/development/wordpress_sites.yml    
    ##### NOTE: Open and configure
6.  trellis/group_vars/development/vault.yml              
    ##### NOTE: Make sure that "vault_wordpress_sites:" matches "wordpress_sites" above
7.  `cd trellis && vagrant up`
8.  Enter computer admin password
9.  `composer create-project roots/sage your-theme-name dev-master`
