Instruction how to deploy BlackDoctor to AWS:
Please use AWS Cloudformation with attached templates
1. Deploy basic template - vpc-and-basic-template.yaml
2. Deploy ecr, cognito, s3, iam templates
3. Deploy s3 template
4. Deploy RDS template
5. Deploy ECS template


Please adjust some specific configuration according product requirments. You can do it with template or manualy.
Setup required numbers of services in ECS according product requirments.
Setup required numbers of tasks in ECS according product requirments.

For backend pipeline please use pipeline-backend.yml.
Please add all ENV varriables into bitbucket pipeline with secured options.
For frontend pipeline please use pipeline-frontend.yml.
Please add all ENV varriables into bitbucket pipeline with secured options.

Review pipeline runing job.
