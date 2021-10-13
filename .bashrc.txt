echo " Hello..Welcome to Archana Terminal.. Have a good day..!!"

alias ls="ls -l -a"
alias home="cd .. && echo 'sucessfully navigated to previous directory'"

function mkd () {
        mkdir -p $1
        cd $1
}
