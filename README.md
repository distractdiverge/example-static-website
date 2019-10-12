# Example Static Website
This is a rather-simple static website. 
This is built using typescript, react and webpack.

## Getting Started

1. Clone this Repo
    ```
    git clone git@github.com:alexlapinski/example-static-website.git
    ```
2. Install NPM dependencies
    ```
    npm install
    ```
3. Build JS via Webpack
    ```
    npm run build
    ```
4. Build Docker Image
    ```
    docker build -t <image_name>:<tag_name> .
    ```
5. Run the Docker Image
    ```
    docker run -d -p 80:80 <image_name>:<tag_name>
    ```
6. Open the browser at ```http://localhost```

## Technologies Used
Inspiration for example project: [React & Webpack Tutorial](https://www.typescriptlang.org/docs/handbook/react-&-webpack.html).
* [React](https://reactjs.org/)
* [Typescript](https://www.typescriptlang.org/)
* [Webpack](https://webpack.js.org/)
* [Docker](https://www.docker.com/)
* [Nginx](https://www.nginx.com/)
