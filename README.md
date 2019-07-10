# Searching for existing Docker images

```
docker search <image-name>
```
To search for docker images that has the text 'Redis',
try the following command

```
docker search redis
```
<pre>         
<font color="#8AE234"><b>gnanavad@gnanavad-Inspiron-15-3567</b></font>:<font color="#729FCF"><b>~</b></font>$ docker search redis | head -5
NAME                             DESCRIPTION                                     STARS               OFFICIAL            AUTOMATED
redis                            Redis is an open source key-value store that…   7083                [OK]                
bitnami/redis                    Bitnami Redis Docker Image                      119                                     [OK]
sameersbn/redis                                                                  75                                      [OK]
grokzen/redis-cluster            Redis cluster 3.0, 3.2, 4.0 &amp; 5.0               51                                      
<font color="#8AE234"><b>gnanavad@gnanavad-Inspiron-15-3567</b></font>:<font color="#729FCF"><b>~</b></font>$ 
</pre>


