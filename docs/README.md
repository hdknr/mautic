# Mautic

## Merge Staging

~~~bash
$ git remote add mautic https://github.com/mautic/mautic.git
.
~~~

~~~bash
$ git checkout staging
$ git fetch mautic
$ git merge mautic/staging
$ git checkout study
$ git merge staging
.
~~~
