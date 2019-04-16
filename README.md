# Google Cloud Function examples

Example code to infer Google Cloud AI Platform models from Google Cloud Functions

### Example Endpoints

Inference Endpoint:

* get_demo_inference_endpoint

Meta Data Endpoint:

* get_demo_inference_meta_endpoint


### Deployment

Set your project as default GCP project with
```
$ gcloud config set project shipyard-231822
```

and then deploy the endpoints with
```
$ gcloud functions deploy <ENDPOINT_NAME> --entry-point <FUNCTION_NAME> --runtime python37 --trigger-http
```