server startup:
CDN:
nohup ./goflyway -k="doubi233" -l=":80" -proxy-pass="http://kernel.ubuntu.com/~kernel-ppa/mainline/" > /tmp/goflyway.log 2>&1 &^C
http:
nohup ./goflyway -k="doubi233" -l=":80" > /tmp/goflyway.log 2>&1 &


client startup:
CND:
goflyway.exe -up="cf://gong.tk:8080" -k="doubi233" -l=":8100" 
pause>nul


http:
goflyway.exe -up="107.173.50.2:8880" -k="doub.io" -l=":8100" 
pause>nul





