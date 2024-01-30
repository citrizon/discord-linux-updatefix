# discord-linux-updatefix
This is a small fix for Discord users on Linux. It's a wrapper bash script that checks the launcher version and updates it through build_info.json

### Dependencies
`bash` (for script execution)<br>
`curl` (for fetching latest version from discord website)<br>
`sed` (for changing build_info values)<br>
`grep` (for filtering version number from fetched data)
