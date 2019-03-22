# RunDirscraper

This is a docker file that will run dirscarper (by Collian-Collins https://github.com/Cillian-Collins/dirscraper) against a target url and output the results to a file.

> docker run --rm -v &lt;Local Dir>:/opt/output --env url=&lt;URL> --env filename=output.txt sburris/DirScraper