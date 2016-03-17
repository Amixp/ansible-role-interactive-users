Universal role that sets up an accounts for user who will be logging in and doing some manual work.

 Supported vars (all optional):
 - interactive_users (default: []) - each item shall contain
   - username
   - zsh_theme (default: blinks) - name of oh-my-zsh theme
   - managed_services - list of services (names) the user is allowed to restart using sudo (always set to [] if not used!)
   - groups - additional groups to add user to
   - authorize_local_key (default: false) - authorizes local ssh key
   - authorized_keys - list of ssh keys to authorize (always set to [] if not used!)
   - ssh_config_path - path to ssh config template
