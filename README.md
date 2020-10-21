#srm
What should be done
Implement srm (secure file deletion) command. The command works like a regular rm, but instead of deleting it, it compresses it with the gzip utility and moves it to the ~ / RECYCLE directory (the trash can), in turn, files that have been there for more than seven days are automatically deleted from RECYCLE. Deleting old files should be activated after calling srm
