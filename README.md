#### About

This is a very simple example without proper validation and using verbatim file names from the client. Make sure you always validate the file’s name and contents e.g. using [fileinfo](http://php.net/fileinfo), and generate a custom filename or use another method of ensuring you’re not overwriting an existing file. You may also wish to put file type and size limits in place.

#### Notice

Requires the following envvar

 * AWS_ACCESS_KEY_ID=xxx
 * AWS_SECRET_ACCESS_KEY=xxx
 * S3_BUCKET=xxx

The ACL for the uploaded file so it’s publicly readable. If you want different permissions, adjust the example accordingly. You can also use a bucket policy to define what the default permissions for uploaded files in a bucket should be.
