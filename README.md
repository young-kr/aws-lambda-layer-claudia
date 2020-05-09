# aws-lambda-layer-claudia
Deployment AWS Layers with ClaudiaJS

1. Make directory for AWS Layers. The directory name SHOULD BE 'nodejs'. It is AWS' rule.
ex) mkdir nodejs && cd nodejs

2. Initialize directory.
ex) npm init -y

3. Install node modules what you need
ex) $ npm i moment aws-sdk aws-serverless-express express

4. Compress the 'nodejs' directory with zip.
ex) Directory structure should be ...
    nodejs  - node_modules      - ...
            - package.json
            - package-lock.json

5. Create AWS Layers
  - Set name
  - Select zip file to upload
  - Set runtime (use same runtime with AWS Lambda function)

6. Go to your AWS Lambda function console and add this AWS Layer. That's it.
