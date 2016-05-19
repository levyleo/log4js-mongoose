
# log4js-mongoose

NOTE: Under development.

## installation

npm install log4js-mongoose 

## usage

	var log4js = require('log4js'), 
		log4jsMongo = require('log4js-mongoose')
	
	log4js.addAppender(log4jsMongo.appender())
	
	log4js.getLogger().info('Ready to log!')

