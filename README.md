# OctoClient

### Python client library for OctoPrint REST API

Work in progress... 

* General information
    - Authorization
    - Content Type
    - Encoding
    - Cross-origin requests
* ~~Version information~~
* Apps
    - Session Keys
        - Workflow
        - Obtaining a temporary session key
        - Verifying a temporary session key
        - Creating the signature
        - Testing your implementation
* Connection handling
    - ~~Get connection settings~~
    - ~~Issue a connection command~~
        - ~~Connect~~
        - ~~Disconnect~~
        - ~~Fake_ack~~
* File operations
    - ~~Retrieve all files~~
    - ~~Retrieve files from specific location~~
    - ~~Upload file or create folder~~
    - ~~Retrieve a specific file’s or folder’s information~~
    - Issue a file command
        - ~~Select~~
        - Slice (TODO: profile.* and position)
        - ~~Copy~~
        - ~~Move~~
    - ~~Delete file~~
* Job operations
    - Issue a job command
        - ~~Start~~
        - ~~Cancel~~
        - ~~Restart~~
        - Pause
            - Pause
            - Resume
            - ~~Toggle~~
    - ~~Retrieve information about the current job~~
* Languages
    - ~~Retrieve installed language packs~~
    - Upload a language pack
    - ~~Delete a language pack~~
* Log file management
* Printer operations
    - ~~Retrieve the current printer state~~
    - ~~Issue a print head command~~
        - ~~Jog~~
        - ~~Home~~
        - ~~Feedrate~~
    - ~~Issue a tool command~~
        - ~~Target~~
        - ~~Offset~~
        - ~~Select~~
        - ~~Extrude~~
        - ~~Flowrate~~
    - ~~Retrieve the current tool state~~
    - ~~Issue a bed command~~
        - ~~Target~~
        - ~~Offset~~
    - ~~Retrieve the current bed state~~
    - ~~Issue an SD command~~
        - ~~Init~~
        - ~~Refresh~~
        - ~~Release~~
    - ~~Retrieve the current SD state~~
    - ~~Send an arbitrary command to the printer~~
* Printer profile operations
    - ~~Retrieve all printer profiles~~
    - Add a new printer profile
    - Update an existing printer profile
    - ~~Remove an existing printer profile~~
* Settings
    - ~~Retrieve current settings~~
    - ~~Save settings~~
    - Regenerate the system wide API key
* Slicing
    - ~~List All Slicers and Slicing Profiles~~
    - ~~List Slicing Profiles of a Specific Slicer~~
    - ~~Retrieve Specific Profile~~
    - Add Slicing Profile
    - ~~Delete Slicing Profile~~
* System
    - ~~List all registered system commands~~
    - ~~List all registered system commands for a source~~
    - ~~Execute a registered system command~~
* Timelapse
    - ~~Retrieve a list of timelapses and the current config~~
    - ~~Delete a timelapse~~
    - ~~Issue a command for an unrendered timelapse~~
        - ~~Render~~
    - ~~Delete an unrendered timelapse~~
    - Change current timelapse config
* User
    - ~~Retrieve a list of users~~
    - ~~Retrieve a user~~
    - ~~Add a user~~
    - Update a user
    - ~~Delete a user~~
    - Reset a user’s password
    - ~~Retrieve a user’s settings~~
    - Update a user’s settings
    - ~~Regenerate a user’s personal API key~~
    - ~~Delete a user’s personal API key~~
* Util
    - Test paths or URLs
        - Path
        - URL
        - Server
* Wizard
    - ~~Retrieve additional data about registered wizards~~
    - ~~Finish wizards~~