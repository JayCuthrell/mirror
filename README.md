# mirror

Something like this...

```
wget --mirror \
--page-requisites \
--adjust-extension \
--span-hosts \
--convert-links \
--restrict-file-names=windows \
--domains=sunday.fudge.org,s3.amazonaws.com,gstatic.com \
--no-parent 
--no-clobber 
--reject-regex utm_ 
-P2022-06-11 
https://jaycuthrell.com/newsletter/
```
