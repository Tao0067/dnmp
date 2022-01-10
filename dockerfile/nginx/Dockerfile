FROM nginx:1.19.1-alpine
#维护者信息
MAINTAINER tao "0140445s"
#时区
ENV TZ Asia/Shanghai
RUN date -R
#容器启动时执行指令
CMD ["nginx", "-g", "daemon off;"]