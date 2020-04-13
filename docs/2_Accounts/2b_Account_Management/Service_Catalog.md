# AWS Service Catalog

If you want to give your enduser permission to luanch a product you need this policy created and attached.

* **Exam Tips:**
  * There's a requirement for endusers to deploy products that they don't have permissions to do otherwise, in a self-service way.

```JSON
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "servicecatalog:ProvisionProduct"
                ],
                "Resource": "*"
        }
    ]
}
```