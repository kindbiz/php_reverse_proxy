A cloned version from 7ghost

Add NGINX config
```
if (-e $request_filename){break;}
rewrite . /index.php last;
```
