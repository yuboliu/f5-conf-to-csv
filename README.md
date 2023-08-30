# f5-conf-to-csv
This is used to read a bigip.conf from an F5 LTM and write CSV files of its configuration. 

This script was tested on Mac and requires Python 3.9+

## Usage 

``` 
chmod 755 f5-conf-to-csv.py
./f5-conf-to-csv.py
```

These CSV files could then be imported into Excel or another spreadsheet for review

## Known Issues

Import of the iRules does not work correctly in Excel... 

## 更新
1、f5-conf-to-csv.py 会在当前目录下查找所有.conf配置文件作为输入，输出文件结构化存放在Output/{文件名}/下，最后根据配置文件为单位，将所有输出的csv文件合并成一个Excel工作薄。
