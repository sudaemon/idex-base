FROM		phusion/baseimage:0.9.18
MAINTAINER	sudaemon <sudaemon@ya.ru>

ADD		. /pd_build

RUN		/pd_build/install.sh
CMD		["/sbin/my_init"]
EXPOSE	80 443
