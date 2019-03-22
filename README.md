# RunDirscraper

This is a docker file that will run dirscarper (by Collian-Collins https://github.com/Cillian-Collins/dirscraper) against a target url and output the results to a file.

> docker run --rm -v <Local Dir>:/opt/output --env url <URL> --env filename output.txt rundirscraper