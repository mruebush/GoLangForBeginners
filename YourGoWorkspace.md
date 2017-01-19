##Go Workspace: How Go Wants You to Lay Out Your Code

Go requires that you put your code in a workspace. A workspace is a directory with three sub-directories:
*src
*pkg
*bin

You should keep all your projects under a single workspace. This makes it easier to to depend on your own code and share common third-party packages.


