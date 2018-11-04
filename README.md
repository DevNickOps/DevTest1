<<<<<<< HEAD
<<<<<<< HEAD
# ****Dev environment****
# Install Docker on your local machine
# Run Docker Application
# In your terminal run following command
#   docker run -d -p 80:80 richarvey/nginx-php-fpm
# You should be able to access the phpinfo page from http://localhost

# ****AWS environment****
# Upload and run infrastructure.yaml template in CloudFormation
# Wait till the infrastructure stack fully provisioned
# Upload and run fargate.yaml template in Cloudformation
# Wait till the fargate stack fully provisioned
# Access the phpinfo page from the URL exported from the output section of fargate stack

#****CICD pipeline*****   
# The pipeline sets up auto provisioning of both infrastructure stack and fargate stack
# A new version of either infrastructure.yaml and fargatae.yaml pushed to Github repo will trigger auto update to the stack
# The pipeline cloudformation template is stored in the URL below, to run it provide this URL to S3 template URL in cloudformation Select Template screen
# https://devtestpipeline.s3.amazonaws.com/pipeline.yaml?AWSAccessKeyId=AKIAIT33HGEBTQUR3FTQ&Signature=z54kISOG%2Bz2gxyAv%2FkHJ6DVNOiA%3D&Expires=1541926863
=======
# DevTest1
>>>>>>> e2391377387a936b71f57ec53fbc8db8030d4b84
=======

>>>>>>> b71d3630fe1b18c3b024304f23733aa90d5b3003
