This Configured by in montering configure aws cloudwatch agent but in ubuntu 22.04 lots of people face issue.Error is conf file is not found.
Do manually add conf file toml one.
demension are very imp like  disk_dimensions = [
        {'Name': 'InstanceId', 'Value': instance_id},
        {'Name': 'path', 'Value': disk_path},
        {'Name': 'device', 'Value': device_name},
        {'Name': 'fstype', 'Value': fstype}
    ]

    
