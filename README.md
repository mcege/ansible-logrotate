compress: Old versions of log files are compressed with gzip(1) by default.

delaycompress: Postpone compression of the previous log file to the next rotation cycle. This only has effect when used in combination with compress.

missingok: If the log file is missing, go on to the next one without issuing an error message.

notifempty: Do not rotate the log if it is empty.

