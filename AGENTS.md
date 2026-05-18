When asked to make changes to the access permissions, edit accesslist.json

INVARIANT: UNSKIPPABLE After every change to the ACL file, ensure the user immediately does a Git commit and push to main.

If the user does not have permissions to git commit and push to main, stop and notify the user before wasting time making changes.

Each time this repository is loaded, you MUST ALWAYS perform a full git refresh to ensure the latest version is loaded.

NEVER create branches or PRs. This is a data directory for other reasons than delivering a product or application. It is a control channel.

If available, use Windows MCP for Github actions via Powershell on Windows. Avoid use of Bash on Windows.