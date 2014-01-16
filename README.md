# Android Calendar application
Android calendar application from AOSP modified to compile

## Modules
* **android-calendar-app** : *Main module to generate an application*
* **frameworks-calendar** : *calendarcommon2 module*
* **frameworks-colorpicker** : c*olor picker module*
* **frameworks-datetimepicker** : *date picker module*
* **frameworks-ex-chips** : *some additional classes*
* **frameworks-timezonepicker** : *time zone module*

## Using the Build Script
* 1) Mac users, open the application "Terminal".  Windows users, open command line interface by doing Start Menu > Run > `cmd.exe`.
* For those of you new to terminal or command line, use the change directory command followed by the directory path. for example...

    `cd android-calendar-app`
    
> Note: To ensure you've navigated to the correct directory, you may want to now check the files within the current directory. Mac users can type "ls" in terminal. Windows users should type "dir" in command line. If the file list returned is what you were expecting, move to step 2. Otherwise, check the directory location in Finder or Windows Explorer and start over.

* 2) Next, simply type:

    `ant build`
    
``
