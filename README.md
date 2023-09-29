# Enable bash completion on mac OS

# Download the file and source it and execute the below commands

git clone https://github.com/kthamel/bash-completion-mac.git

cd bash-completion-mac

source git-completion.bash

cp -rv git-completion.bash /opt/homebrew/etc/bash_completion.d/

# then check the bash completion