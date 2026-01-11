#
# Executes commands at the start of an interactive session.
#
# Authors:
#   Sorin Ionescu <sorin.ionescu@gmail.com>
#

# Source Prezto.
if [[ -s "${ZDOTDIR:-$HOME}/.zprezto/init.zsh" ]]; then
  source "${ZDOTDIR:-$HOME}/.zprezto/init.zsh"
fi

# Customize to your needs...
prompt_context() {}

alias vp_hadoop_socks='ssh -vND localhost:7999 vpbastion'                                                                                                      
alias hadoop_socks='ssh -vND localhost:7999 stbastion'

export GIT_EDITOR=vim
export PATH=$PATH:/usr/local/protobuf-2.5.0/bin
export PATH=$PATH:/Users/ts_24/hadoop-2.7.5/bin
export PATH=$PATH:/usr/local/spark/bin
export PATH=$PATH:/Users/ts_24/anaconda3/bin

export CASSANDRA_HOME_DIR=/usr/local/Cellar/cassandra/3.11.6
export SBT_HOME=/usr/local/Cellar/sbt@0.13/0.13.18/bin

export PATH=$PATH:$SBT_HOME
hadoop_itms8 () {
  export HADOOP_USER_NAME=amp_recommendations
  export HADOOP_CONF_DIR=$HOME/hadoop-conf/ISitms8
}

if [[ -s "${ZDOTDIR:-$HOME}/.zprofiles/cassandra_profile.zsh" ]]; then
  source "${ZDOTDIR:-$HOME}/.zprofiles/cassandra_profile.zsh"
fi

if [[ -s "${ZDOTDIR:-$HOME}/.zprofiles/reco_apps_profile.zsh" ]]; then
  source "${ZDOTDIR:-$HOME}/.zprofiles/reco_apps_profile.zsh"
fi

azkaban_start_local () {
	cd $HOME/azkaban/azkaban-solo-server/build/install/azkaban-solo-server
	./bin/start-solo.sh
	cd $HOME
}

alias hparquet="hadoop jar ~/parquet-tools-1.8.2.jar"
alias jparquet="java jar ~/parquet-tools-1.8.2.jar"

alias pv_hadoop_socks='ssh -N -D 7999 -A pvbastion'

JAVA_HOME="$(/usr/libexec/java_home -v 11.0.6)"
export JAVA_HOME
PATH=$JAVA_HOME/bin:$PATH
export PATH


alias python=/usr/local/bin/python3

# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/Users/ts_24/anaconda3/bin/conda' 'shell.zsh' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/Users/ts_24/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/ts_24/anaconda3/etc/profile.d/conda.sh"
    else
        export PATH="/Users/ts_24/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<

alias blobby='aws --endpoint-url https://blob.mr3.simcloud.apple.com --cli-read-timeout 300'

