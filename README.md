# meteor-build-deploy
Automation docker container to build and deploy with Meteor Up (mup).

## Programs
- node
- meteor
- git
- sudo
- curl
- python
- build-essential
- ca-certificates
- locales
- unicode-data

## User
- builder

## Extra features:
 * Can upload pictures to AWS S3 using `s3-upload` which is added to the PATH.

### Requires environment variables:
  AWS_S3_ACCESS_KEY            access key ('' for upload to public writable bucket)
  AWS_S3_SECRET_ACCESS_KEY     secret key ('' for upload to public writable bucket)
