# Node App for Image Uploading

This is a simple Node.js application that allows users to upload images using an endpoint. 

## Prerequisites
- Node.js installed on your local machine
- Postman app installed on your local machine

## Installation
1. Clone the repository to your local machine using the following command: 

    ```
    git clone https://github.com/impoiler/image-uploader.git
    ```
    
2. Navigate to the project directory: 

    ```
    cd image-uploader
    ```
    
3. Install the dependencies by running the following command: 

    ```
    npm install
    ```

## Usage
1. Start the application by running the following command in your terminal: 

    ```
    npm start
    ```
    
2. Open the Postman app and create a new request. Set the HTTP method to POST and the URL to `http://localhost:3000/upload`.

3. Select the `Body` tab and choose `form-data`.select `File` as the type.

4. Choose an image from your local machine and click `Send`.

5. The response will contain the URL of the uploaded image.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
