* * * * * command-to-execute
│ │ │ │ │
│ │ │ │ └─── Day of week (0-7, where 0 and 7 = Sunday)
│ │ │ └───── Month (1-12)
│ │ └─────── Day of month (1-31)
│ └───────── Hour (0-23)
└─────────── Minute (0-59)



# Every minute
* * * * * command

# Every hour at minute 0 (top of the hour: 1:00, 2:00, 3:00...)
0 * * * * command

# Every day at 2:30 AM
30 2 * * * command

# Every Monday at 9:00 AM
0 9 * * 1 command

# Every 15 minutes
*/15 * * * * command

# Every 30 minutes
*/30 * * * * command

# Every 6 hours
0 */6 * * * command

# Every day at midnight
0 0 * * * command

# First day of every month at midnight
0 0 1 * * command

# Every weekday (Mon-Fri) at 6:00 PM
0 18 * * 1-5 command

# Every weekend (Sat-Sun) at 10:00 AM
0 10 * * 6-7 command

# Multiple times: 8 AM, noon, 6 PM every day
0 8,12,18 * * * command
```

## Special Characters

- **`*`** = Every (any value)
- **`*/n`** = Every n units (e.g., `*/5` in minutes = every 5 minutes)
- **`,`** = List separator (e.g., `1,15` = run at 1 and 15)
- **`-`** = Range (e.g., `1-5` = Monday through Friday)
- **`/`** = Step values (e.g., `*/2` = every 2 units)

## Day of Week Values
```
0 or 7 = Sunday
1 = Monday
2 = Tuesday
3 = Wednesday
4 = Thursday
5 = Friday
6 = Saturday



0 * * * * /home/shahboz/Pose_estimation/gait_analysis-app/cleanup_uploads.sh
Translation:

0 = at minute 0
* = every hour
* = every day of month
* = every month
* = every day of week