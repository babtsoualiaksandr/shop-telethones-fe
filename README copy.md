## 3 - S3 bucket has been created and configured properly. The app has been uploaded to the bucket and is available though the Internet. Nothing else has been done. (Link to S3 bucket/website is provided. There is no Pull Request in the FE repository.)
[Link to S3 bucket: http://myfirstapprss.s3-website-eu-west-1.amazonaws.com//](http://myfirstapprss.s3-website-eu-west-1.amazonaws.com//)
## 4 - In addition to the previous work a CloudFront distribution is created and configured properly and the site is served now with CloudFront and is available through the Internet over CloudFront URL, not S3-website link (due to changes in bucket’s policy...). (Link to CloudFront website is provided. S3-website shows 403 Access Denied error. There is no Pull Request in the FE repository.)
[CloudFront website: dumj6fy0dr0jh.cloudfront.net](dumj6fy0dr0jh.cloudfront.net)
## 5 - Serverless-finch and serverless-single-page-app plugins are added and configured. The app can be built and deployed by running npm script command. (Link to CloudFront website is provided. PR with all changes is submitted in the FE repository and its link is provided for review.)
[Link to CloudFront website: https://d229bhl89r9mxt.cloudfront.net/](https://d229bhl89r9mxt.cloudfront.net/)

### Serverless: This deployment will:
Serverless: - Upload all files from 'build' to bucket 'mysecondapprss'
? Do you want to proceed? true
Serverless: Looking for bucket...
Serverless: Bucket found...
Serverless: Deleting all objects from bucket...
Serverless: Retaining existing bucket configuration...
Serverless: Retaining existing bucket policy...
Serverless: Retaining existing tags...
Serverless: Retaining existing bucket CORS configuration...
Serverless: Uploading client files to bucket...
Serverless: Success! Your site should be available at http://mysecondapprss.s3-website-eu-west-1.amazonaws.com/

> store@0.1.0 cloudfront:invalidateCache /Users/alexander/Documents/Node_JS_AWS/Task2/nodejs-aws-fe
> sls invalidateCloudFrontCache

Serverless: Web App Domain: d229bhl89r9mxt.cloudfront.net
Serverless: Invalidating CloudFront distribution with id: E2LQXZK7Y0ZC0Z
Serverless: Successfully invalidated CloudFront cache


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:  
You can use NPM instead of YARN (Up to you)  

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
