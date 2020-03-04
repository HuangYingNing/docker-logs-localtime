# docker-logs-localtime
replace all UTC dates to local dates for command docker logs.

install:
# git clone https://github.com/HuangYingNing/docker-logs-localtime.git /usr/local/docker-logs-localtime && ln -s /usr/local/docker-logs-localtime/docker-logs-localtime /usr/local/bin/docker-logs-localtime && chmod +x /usr/local/docker-logs-localtime/docker-logs-localtime /usr/local/bin/docker-logs-localtime

or:
# wget -O /usr/local/bin/docker-logs-localtime https://raw.githubusercontent.com/HuangYingNing/docker-logs-localtime/master/docker-logs-localtime && chmod +x /usr/local/bin/docker-logs-localtime

usage: docker logs -t container_name 2>&1 | docker-logs-localtime

