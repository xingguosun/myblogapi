FROM mysql:5.7

#  set timezome
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
ADD ../../sql/myblog.sql /docker-entrypoint-initdb.d