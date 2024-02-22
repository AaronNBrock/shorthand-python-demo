# shorthand-python-demo

## to deploy

```bash
gcloud functions deploy python-http-function \
    --gen2 \
    --runtime=python312 \
    --region=us-central1 \
    --source=. \
    --entry-point=hello_http \
    --trigger-http \
    --allow-unauthenticated
```