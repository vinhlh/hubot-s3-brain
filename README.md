# hubot-s3-brain
A S3 brain for Hubot with latest AWS JS SDK
This is a lightly modified version of hubot-scripts/s3-brain.coffee by IrishStyle. 

## Configuration
hubot-s3-brain can be configured with environment variables:

```
#   HUBOT_S3_BRAIN_ACCESS_KEY_ID      - AWS Access Key ID with S3 permissions
#   HUBOT_S3_BRAIN_SECRET_ACCESS_KEY  - AWS Secret Access Key for ID
#   HUBOT_S3_BRAIN_BUCKET             - Bucket to store brain in
#   HUBOT_S3_BRAIN_SAVE_INTERVAL      - [Optional] auto-save interval in seconds
#                                     Defaults to 30 minutes
#   HUBOT_S3_BRAIN_REGION             - Region which Bucket belongs to
#   HUBOT_S3_BRAIN_FILE_NAME          - [Optional] brain file name
#                                     Defaults brain-dump.json
```
