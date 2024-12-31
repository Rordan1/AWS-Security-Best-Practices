
# Manually creating a trail due to autocreate implications
![location and name](Screenshot_25-11-2024_121752_us-east-1.console.aws.amazon.com.jpeg)

## Location and name
![default is to log all API operations that read and modify resources.](Screenshot_25-11-2024_122355_us-east-1.console.aws.amazon.com.jpeg)

## Default settings are to log all API operations that read and modify resources
![alt text](Screenshot_25-11-2024_12398_us-east-1.console.aws.amazon.com.jpeg)

## Extra precaution is to use this custom SCP to prevent logging being turned off by non root users
![alt text](<Screenshot 2024-11-25 at 19-11-49 Mitigate log manipulation AWS Organizations Global.png>)

## Can view the amount of bucket storage used
![alt text](Screenshot_10-12-2024_221234_us-east-1.console.aws.amazon.com.jpeg)

# Delete irrelevant logs or create lifecylce rules to save money

## Since this is a demo I can use the root account to delete the cloudtrail bucket destination which is consuming the majority of data

![alt text](Screenshot_10-12-2024_221559_us-east-1.console.aws.amazon.com.jpeg)

## It's also possible to create lifecycle policies which move older versions to cheaper less reliable storage after a specified amount of time, but are still availble if needed.

![alt text](Screenshot_31-12-2024_11432_us-east-1.console.aws.amazon.com.jpeg)