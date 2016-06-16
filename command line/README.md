Commnad line 'commands'

Get files count: It will search for "*.js" files in current directory (.) by excluding (-path ./vendor) and prints the totals count
$ find . -path ./vendor -prune -o -name "*.js" -print | wc -l
