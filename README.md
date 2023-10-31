# pmac770poller
Reads data from PMAC770 power meter wth 100/5A CT's
Script is based on  Rio's code (https://github.com/riogrande75/sdm630poller) and adapted accordingly  for PMAC770 (http://en.pmac.com.cn/product.php?id=39)
This script reads data from 2 modbus-rtu powermeters (PMAC770) with modbus ID's 1. This data gets written into a files in the ramdisk (/tmp/ACTsdm630.txt and also in share memory objects. For intertask communication shared memory objects shall be used - the textfiles are for manual verification only. The data can be used e.g. with any logger programm (i.e Jean Marc's meterN, 123Solar) https://github.com/jeanmarc77/meterN https://github.com/jeanmarc77/123solar
