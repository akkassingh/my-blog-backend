# myBlog

Development Server:
1. Create .env file.
2. Set Variables:

    ⋅⋅* MONGO_USERNAME=root
    ⋅⋅* MONGO_PASSWORD=root

3. Install depedencies ```npm i```.

4. Run command ```npm run dev``` for development server.


### Deploying to GCloud.

    1. gcloud auth login
    2. gcloud config set project<PROJECT_ID>
    3. gcloud app deploy
    4. gcloud app browse