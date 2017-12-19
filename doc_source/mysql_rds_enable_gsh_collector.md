# mysql\.rds\_enable\_gsh\_collector<a name="mysql_rds_enable_gsh_collector"></a>

Enables the Global Status History \(GoSH\) to take default snapshots at intervals specified by `rds_set_gsh_collector`\. For more information, see [Managing the Global Status History](Appendix.MySQL.CommonDBATasks.md#Appendix.MySQL.CommonDBATasks.GoSH)\.

## Syntax<a name="mysql_rds_enable_gsh_collector-syntax"></a>

```
CALL mysql.rds_enable_gsh_collector;
```

## Related Topics<a name="mysql_rds_enable_gsh_collector.related"></a>

+ [mysql\.rds\_set\_gsh\_collector](mysql_rds_set_gsh_collector.md)

+ [mysql\.rds\_disable\_gsh\_collector](mysql_rds_disable_gsh_collector.md)

+ [mysql\.rds\_collect\_global\_status\_history](mysql_rds_collect_global_status_history.md)

+ [mysql\.rds\_enable\_gsh\_rotation](mysql_rds_enable_gsh_rotation.md)

+ [mysql\.rds\_set\_gsh\_rotation](mysql_rds_set_gsh_rotation.md)

+ [mysql\.rds\_disable\_gsh\_rotation](mysql_rds_disable_gsh_rotation.md)

+ [mysql\.rds\_rotate\_global\_status\_history](mysql_rds_rotate_global_status_history.md)