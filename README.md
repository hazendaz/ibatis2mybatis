﻿ibatis2mybatis
==============

![mybatis](https://mybatis.org/images/mybatis-logo.png)

The tool is designed around an xslt transformation and some text replacements packaged in an ant task and tries to deliver a good starting point before the more complex work begins.

Usage:
Put Your old ibatis2 sqlmap files in the source folder and execute the ant build file.  Alternatively you can use maven as well to call ant using same process without any need to install ant through 'mvn clean install' or many variations thereof.
The task converts Your sqlmap2 files to myBatis mappers in the destination folder and reports anything it cannot convert in the console.

Have fun and maybe You can post some improvements/bugfixes as this initial version is by no means perfect yet!

Greetings from Frankfurt/Germany

Peter Köhler
