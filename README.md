# Cytizen LinuxDB API

 Simple Deno + MongoDB API. This API stores a database of Linux Distros, so users can get a list of them, share the description of a new one or update them. 
 
 Working on restricting access to ```DELETE``` HTTP Method and a UI for interacting with the API on the website.

I followed [this tutorial](https://www.mongodb.com/developer/languages/rust/getting-started-deno-mongodb/) and changed some things along the way...

## Usage

For testing, this structure must be used:

```json
{
    "id": [int],
    "name": "",
    "current_version": "",
    "desktop_environment": "",
    "package_manager": "",
    "description": ""
}
```

Also, connect to 127.0.0.1:8080/api/distros