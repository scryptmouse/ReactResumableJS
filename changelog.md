### Changelog:}
- 1.1.23
    - Fix and improvements https://github.com/Artear/ReactResumableJS/pull/24
- 1.1.22
    - Remove invalid import
- 1.1.21
    - Fix PropTypes
    - Upgrade React-dom
- 1.1.20
    - Fix https://github.com/Artear/ReactResumableJS/pull/22
    - Fix https://github.com/Artear/ReactResumableJS/issues/21
- 1.1.19
    - Now you can pause, cancel or resume the upload
    - added start button option
    - added pause button option
    - added cancel button option
    - added onStartUpload callback
    - added onPauseUpload callback
    - added onCancelUpload callback
- 1.1.16
    - added option maxFilesErrorCallback
- 1.1.15
    - fixed low performance with the preview image in the file list.
    - added new options.
        - fileNameServer
        - tmpDir
        - chunkSize
        - simultaneousUploads
        - fileParameterName
        - generateUniqueIdentifier
    - updated demo.
- 1.1.13
    - added class disabled on label
- 1.1.12
    - removed "capture", cause some cellphones takes this, to open the cammera, instead open file browse.
- 1.1.11
    - Added MaxFileSize value for size validation (parameter and callback)
    - Added "disabled" param for the file input
- 1.1.10
    - Uploader file input is now contained on a Label for easy styling (when you need to hide file input).
- 1.1.7
    - added uniqid to elements on filelist.
    - added option onFileRemoved.
    - added option showFileList.
    - removed message status.
    - updated example.
- 1.1.6
    - minor fixed
- 1.1.5
    - added custom dropTargetId
- 1.1.4
    - added support to video and others in preview list
    - added npm run demo command
- 1.1.3
    - fixed example
- 1.1.2
    - changed unique identifier
    - changed option onFileSuccess, now return file uploaded and server message
- 1.1.0
    - Removed property options
    - Now all options are properties ( see the example )
    - Refactor: functions to arrow functions