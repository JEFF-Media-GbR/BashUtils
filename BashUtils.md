# cd to path of script
`
cd "$(dirname ${BASH_SOURCE[0]})"
`
# Heredoc to file
`
cat << EOF > /tmp/yourfilehere
These contents will be written to the file.
        This line is indented.
EOF
`
