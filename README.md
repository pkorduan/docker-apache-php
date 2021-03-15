# docker-apache-php
Simple Apache2 with php7 based on the latest debian image. It is used to run php Scripts for web applications and on CLI and to support access to Postgres Database. cron and dialog are used to run time based jobs and log file analysis.

# Changelog

## 1.0.4
	* Start cron before apache service at the end of the Dockerfile
## 1.0.3
	* Enable PHP Modules: gd, json, xml
## 1.0.2
	* Start cron service
