A cloned version from 7ghost

Add NGINX config
  location /
{
if (!-e $request_filename){
    rewrite . /index.php last;
  }
}
