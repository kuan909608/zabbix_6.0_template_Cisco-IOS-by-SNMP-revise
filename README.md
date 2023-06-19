改善 Cisco Catalyst 9200、9300 Temperature sensors trigger 是固定 threshold 導致誤報警的情況。
新增 Temperature Discovery 的 {#SNMPVALUE}: Temperature threshold，並將 trigger 改為與 Temperature threshold 比較。
原先的 macro {$TEMP_CRIT} 與 {$TEMP_WARN} 功能改為"與系統閥值相減為觸發值"

Improve the triggers of Cisco Catalyst 9200, 9300 Temperature sensors to avoid false alarms caused by fixed thresholds.
Add Temperature Discovery: {#SNMPVALUE}: Temperature threshold, and modify the triggers to compare with the Temperature threshold.
Update the functionality of the macros {$TEMP_CRIT} and {$TEMP_WARN} to "subtract the system threshold to obtain the trigger value".
