First, build image:
`docker build -t converter .`

Then launch app:
`docker run --rm -v $(pwd)/dwg:/root/dwg converter ./dwg2svg /root/dwg/<dwg file name>`

More info: [qcad-command-line-tools](http://www.qcad.org/en/qcad-documentation/qcad-command-line-tools)
