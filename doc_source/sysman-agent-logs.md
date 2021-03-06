# View SSM Agent Logs<a name="sysman-agent-logs"></a>

SSM Agent writes information about executions, scheduled actions, errors, and health statuses to log files on each instance\. You can view log files by manually connecting to an instance, or you can automatically send logs to Amazon CloudWatch Logs\. For more information about sending logs to CloudWatch, see [Monitoring Instances with AWS Systems Manager](monitoring.md)\.

You can view SSM Agent logs on Linux instances in the following locations\.
+ `/var/log/amazon/ssm/amazon-ssm-agent.log`
+ `/var/log/amazon/ssm/errors.log`

SSM Agent `sterr` and `stdout` files are written to the following directory: /var/lib/amazon/ssm\.

For information about enabling SSM Agent debug logging, see [Enable SSM Agent Debug Logging](troubleshooting-remote-commands.md#systems-manager-ssm-agent-debug-log-files)\.

For more information about `cihub/seelog` configuration, see the [Seelog Wiki](https://github.com/cihub/seelog/wiki) on GitHub\. For examples of `cihub/seelog` configurations, see the [cihub/seelog examples](https://github.com/cihub/seelog-examples) repository on GitHub\. 