<!-- pre-align:aligned sig=8f1065990f8d -->

<a id="database-rds-for-ms-sql-release-notes"></a>
## Database > RDS for MS-SQL > Release Notes { #database-rds-for-ms-sql-release-notes }

<a id="march-14-2023"></a>
### March 14, 2023 { #march-14-2023 }
<a id="march-14-2023-feature-improvements"></a>
#### Feature Improvements

* Made improvements so that, when restoring to an object storage backup, events for backup type errors are logged

<a id="march-14-2023-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where, when restoring to an object storage backup, version error events are not logged

<a id="february-14-2023"></a>
### February 14, 2023 { #february-14-2023 }
<a id="february-14-2023-feature-improvements"></a>
#### Feature Improvements

* Added a feature to select whether to enable MS-SQL monitoring

<a id="january-10-2023"></a>
### January 10, 2023 { #january-10-2023 }
<a id="january-10-2023-feature-improvements"></a>
#### Feature Improvements

* Removed the full backup to object storage feature
* Made improvements to export full backups during differential backup to object storage
* Made improvements to select current databases during differential backup to object storage
* Made improvements to restore differential backups when restoring from backups in object storage
* Made improvements to select backed up databases when exporting backups to object storage

<a id="january-10-2023-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where, when restoring backups in object storage, differential backups cannot be restored

<a id="december-13-2022"></a>
### December 13, 2022 { #december-13-2022 }
<a id="december-13-2022-feature-improvements"></a>
#### Feature Improvements

* Made modifications so that multiple security groups can be selected and deleted

<a id="december-13-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where, when viewing error logs, an error occurs when the log is too long

<a id="november-15-2022"></a>
### November 15, 2022 { #november-15-2022 }
<a id="november-15-2022-feature-improvements"></a>
#### Feature Improvements
* Added a feature to proceed with auto backup when log backup fails
* Added a feature to activate or deactivate auto backup and log backup
* Added a feature to select the temp DB location

<a id="october-11-2022"></a>
### October 11, 2022 { #october-11-2022 }
<a id="october-11-2022-bug-fixes"></a>
#### Bug Fixes
* Limited the maximum available period for querying error logs to 3 months

<a id="september-14-2022"></a>
### September 14, 2022 { #september-14-2022 }

<a id="september-14-2022-feature-improvements"></a>
#### Feature Improvements

* Made modifications so that, when a parameter that requires a restart is changed, the DB instance restart is not scheduled
* Made improvements so that error logs can be found through infinite scrolling

<a id="september-14-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where database replication occurs twice when changing a single DB instance to a high availability DB instance right after creating database

<a id="august-9-2022"></a>
### August 9, 2022 { #august-9-2022 }

<a id="august-9-2022-feature-improvements"></a>
#### Feature Improvements

* Made modifications so that, when DB connection is unavailable due to changing parameters incorrectly, the parameters can be changed.

<a id="august-9-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where failover fails intermitently

<a id="july-12-2022"></a>
### July 12, 2022 { #july-12-2022 }

<a id="july-12-2022-feature-improvements"></a>
#### Feature Improvements

* Made improvements so that, when backup fails due to insufficient system memory of MS-SQL, the cause is recorded in event log 
* Made improvements so that there is little delay in the log view screen on the console

<a id="july-12-2022-bug-fixes"></a>
#### Bug Fixes

* Made modifications so that, when replicating the selected parameter group, the selection is cleared
* Fixed an issue where log backup fails intermitently
* Made modifications so that a full backup is not performed when log backup fails even before it starts

<a id="june-14-2022"></a>
### June 14, 2022 { #june-14-2022 }

<a id="june-14-2022-feature-improvements"></a>
#### Feature Improvements

* Made improvements so that the outbound direction can be added to security group rules
* Made improvements so that the port can be added to security group rules
* Added SQL Server 2019 Standard (15.0.4223.1) version
* Made improvements so that the parameter group can be applied even when the version of the parameter group applied to the DB instance is low

<a id="june-14-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where it fails when changing only the name of the DB security group
* Fixed an issue where it fails intermittently when deactivating the product

<a id="may-10-2022"></a>
### May 10, 2022 { #may-10-2022 }

<a id="may-10-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where log backup fails intermittently

<a id="march-15-2022"></a>
### March 15, 2022 { #march-15-2022 }

<a id="march-15-2022-added-features"></a>
#### Added Features

* Added maintenance management function

<a id="march-15-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed a bug where `,` could be inserted into numeric parameters

<a id="january-11-2022"></a>
### January 11, 2022 { #january-11-2022 }

<a id="january-11-2022-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where DB instance creation fails intermittently

<a id="december-14-2021"></a>
### December 14, 2021 { #december-14-2021 }

<a id="december-14-2021-feature-improvements"></a>
#### Feature Improvements

* Made improvements so that display the name in addition to CIDR when selecting a subnet while creating an instance
* Changed the data path of the master database to the data volume

<a id="december-14-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed a bug where you could select an event code that cannot be subscribed to when registering or modifying an event subscription
* Fixed a bug where unnecessary storage remained intermittently when deleting a DB instance
* Fixed an issue where, after restarting a DB instance, the DB instance is intermittently changed to connection unavailable status
* Fixed an issue where, when modifying a DB instance, the DB instance is temporarily changed to available status intermittently even though the task is not completed
* Fixed an issue where the disk transfer rate was displayed incorrectly on the server dashboard

<a id="november-9-2021"></a>
### November 9, 2021 { #november-9-2021 }

<a id="november-9-2021-added-features"></a>
#### Added Features

* Added a feature to send email and SMS notifications on scheduled hypervisor migrations

<a id="november-9-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where CloudTrail's response body is truncated if it is long

<a id="november-9-2021-others"></a>
#### Others

* Added billing for root volumes

<a id="october-12-2021"></a>
### October 12, 2021 { #october-12-2021 }

<a id="october-12-2021-feature-improvements"></a>
#### Feature Improvements

* Changed the code so that, when a version error occurs while restoring from backup in object storage, the error is recorded in event log.
* Added performance metrics collection items.
* Modified the error message displayed when backup deletion fails, to indicate in detail which operation caused the failure.
* Added a feature to perform scheduled hypervisor migration on the RDS for MS-SQL web console.

<a id="september-14-2021"></a>
### September 14, 2021 { #september-14-2021 }

<a id="september-14-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed a bug where manual backup could be performed during the rebuilding of monitoring server.
* Fixed a bug where the database operated as if dropping had succeeded even if it failed due to an MS-SQL issue while dropping the database with a drop procedure.

<a id="august-10-2021"></a>
### August 10, 2021 { #august-10-2021 }

<a id="august-10-2021-feature-improvements"></a>
#### Feature Improvements

* Modified to verify the integrity of the file by checking the checksum when uploading/downloading a file.
* Fixed to return an error when the quota is insufficient by performing a quota check in advance when creating instances, changing types, and expanding storage.

<a id="august-10-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where the database items in the web console were incorrectly synchronized when repeatedly creating and deleting databases in instances with high availability.
* Fixed an issue where backups failed intermittently when repeatedly creating and deleting databases in instances with high availability.
* Fixed an issue where it was impossible to restore when trying to restore to a specific point in time.
* Fixed an issue where backups in use for restore could be deleted
* Fixed an issue where the log could not be looked up in SQL Server 2017 Standard (14.0.3294.2)

<a id="july-13-2021"></a>
### July 13, 2021 { #july-13-2021 }

<a id="july-13-2021-added-features"></a>
#### Added Features

* Force restart feature added

<a id="july-13-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed a bug in which the reset button in the event list doesn’t work

<a id="june-15-2021"></a>
### June 15, 2021 { #june-15-2021 }

* Added the notification group feature
* Added user group feature

<a id="may-11-2021"></a>
### May 11, 2021 { #may-11-2021 }

<a id="may-11-2021-feature-updates"></a>
#### Feature Updates

* Added the checkbox that selects all backups

<a id="april-13-2021"></a>
### April 13, 2021 { #april-13-2021 }

<a id="april-13-2021-features-development"></a>
#### Features Development

* Modified the system so that users can select multiple backups and delete them at once
* Modified the system so that object storages can be restored with a different name

<a id="april-13-2021-features-updates"></a>
#### Features Updates

* Modified the system so that instances of which memory is less than 8GB cannot access the high availability feature

<a id="march-9-2021"></a>
### March 9, 2021 { #march-9-2021 }

<a id="march-9-2021-bug-fixes"></a>
####  Bug Fixes

* Added a verification logic to prevent the use of a manual backup of database of which recovery model is `SIMPLE` for restoration of high availability configuration

<a id="february-9-2021"></a>
### February 9, 2021 { #february-9-2021 }

<a id="february-9-2021-feature-updates"></a>
#### Feature Updates

* New instance type supported (x1 type)

<a id="february-9-2021-bug-fixes"></a>
#### Bug Fixes

* Fixed an issue where manual backup of a database of which recovery model is set to `SIMPLE` fails

<a id="january-12-2021"></a>
### January 12, 2021 { #january-12-2021 }

<a id="january-12-2021-feature-development"></a>
#### Feature Development

- Added the Stored Procedure for deleting databases

<a id="january-12-2021-feature-updates"></a>
#### Feature Updates

- Fixed the application to leave additional server events for creating instance
- Fixed the application to display the instance type category in the same manner as in the Compute & Network service
- Fixed the application to leave events on promoted primary servers when an auto failover occurs.

<a id="january-12-2021-bug-fixes"></a>
#### Bug Fixes

- Fixed a bug where an error would occur when restoring a previous backup after an auto failover.
- Fixed a bug where the database of the web console would sometimes be exposed multiple times on a high availability DB instance.
- Fixed a bug where an error would occur when restoring to the point in time right after creating instance
- Fixed a bug where a DB instance with a completed failover would often fail to edit.
- Fixed a bug where the name of a DB instance with a completed failover would not be exposed on the web console usage page under specific conditions.

<a id="december-15-2020"></a>
### December 15, 2020 { #december-15-2020 }

<a id="december-15-2020-feature-development"></a>
#### Feature Development

- High availability DB instance feature added

<a id="october-13-2020"></a>
### October 13, 2020 { #october-13-2020 }

<a id="october-13-2020-bug-fixes"></a>
#### Bug Fixes

- Fixed a bug of DB instance restoration failure where it is rolled back to the time it was created

<a id="september-15-2020"></a>
### September 15, 2020 { #september-15-2020 }

<a id="september-15-2020-feature-updates"></a>
#### Feature Updates

- Updated UX for a more subdivided representation of DB instance status

<a id="september-15-2020-bug-fixes"></a>
#### Bug Fixes

- Fixed a bug of failure to roll back to a certain point of time right after a new database is created
- Fixed a UI bug where the date insertion component failed to operate properly when Japanese was selected

<a id="september-15-2020-others"></a>
#### Others

- Excluded c2.c2m2 instance from instances that can be generated

<a id="august-11-2020"></a>
### August 11, 2020 { #august-11-2020 }

<a id="august-11-2020-feature-updates"></a>
#### Feature Updates

- Updated UX to use DB instance type and storage size of the original DB instance as default

<a id="august-11-2020-bug-fixes"></a>
#### Bug Fixes

- Fixed a bug that only allows restoration to 5 minutes before a desired time point.
- Fixed a bug where attempts to access a DB instance creator page are led to an error page in the absence of a subnet.

<a id="july-14-2020"></a>
### July 14, 2020 { #july-14-2020 }

<a id="july-14-2020-release-of-alpha-service"></a>
#### Release of Alpha Service 

* TOAST Relational Database Service for SQL Server (RDS for MS-SQL) provides Microsoft SQL Server in the cloud environment.
