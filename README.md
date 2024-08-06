This Configured by in monitoring configure aws cloudwatch agent but in ubuntu 22.04 lots of people face issue.Error is conf file is not found
Do manually add conf file toml one. You can use 
'''
sudo vim /opt/aws/amazon-cloudwatch-agent/etc/common-config.toml

'''
demension are very imp like  disk_dimensions = [
        {'Name': 'InstanceId', 'Value': instance_id},
        {'Name': 'path', 'Value': disk_path},
        {'Name': 'device', 'Value': device_name},
        {'Name': 'fstype', 'Value': fstype}
    ]

    
