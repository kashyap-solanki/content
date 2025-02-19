## [Unreleased]


## [19.11.1] - 2019-11-26
- Logging improvement.
- Added the *Max incidents per fetch* parameter, which specifies the maximum number of incidents to retrieve per fetch. The maximum for this parameter is 50.

## [19.11.0] - 2019-11-12
  - Improved implementation of the ***ews-move-item-between-mailboxes*** command.
  -  The email body now prints to context and the War Room for the following commands:
    - ***ews-get-items***
    - ***ews-search-mailbox***

## [19.10.2] - 2019-10-29
- Improved implementation of the ***ews-search-mailbox*** command.
- Added the ***ews-get-items-as-eml*** command.

## [19.9.1] - 2019-09-18
Improved handling of uploaded EMLfiles.

## [19.9.0] - 2019-09-04
- Improved implementation of the ***ews-get-contacts*** command.
- Improved security for the  Exchange 365 Compliance search.
- Added the *get-internal-items* argument to the ***ews-get-items-from-folder*** command, which enables you to retrieve EML and MSF file attachments.
- Improved security within the Docker container.


## [19.8.0] - 2019-08-06
  - Improved memory resource usage.
  - Added the ***ews-mark-items-as-read*** command.
  - Added the *Mark fetched emails as read* parameter to the integration instance configuration. 
  - Improved integration documentation.

