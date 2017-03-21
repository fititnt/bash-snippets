# bash-snippets

## Last user logins

### Full list

`last`

### Full list of unique IPs
`last | tr -s ' ' | cut -d ' ' -f 3 | sort | uniq`
