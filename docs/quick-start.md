# Getting Started with Fabrik Reloaded

## Software Prerequisites

### CMS requirements

- Joomla version 4+
- Fabrik Reloaded latest version

### Server environment

- PHP 8.x.x - preferable is PHP 8.1.x
- Database: MYSQLi or MARIADB
- Image library: GD or Imagemagick
- max_execution_time = 90
- max_input_time = 90
- memory_limit = 512MB
- max_input_vars = 5000
- post_max_size = 256MB
- upload_limit = 256MB


If you are new to Fabrik, your best place to start is with a fresh installation.

## New site install

Follow these steps to get going with Joomla and Fabrik Reloaded

We are assuming you have Joomla installed.

1. Download the latest version from the repo. [LINK]
2. Install the component via the installation area of Joomla. If all goes well you will have a success message of the installation.
3. You are ready to go.

## Upgrading Fabrik Reloaded

We recommend updating via the Joomla installer. You will be notified when a new version is released. This will mean that the code is stable and tested with our Joomla version.

If you would like to test with a new release which is still in development, here is the process to do this.

### Upgrade method: Github

TODO

### Upgrade method: FTP Upload

TODO


## Uninstalling Fabrik Reloaded

When unistalling, please be aware that ALL data is removed. Ensure you have a backup before you proceeed.

- Before uninstalling disable the Fabrik System Plugin.
- Go to Extentions/Manage
- Search for "Fabrik"
- Select to show "All" rows
- Disable "System - Fabrik" (the last plugin)
- Select all Fabrik plugins and "Uninstall"