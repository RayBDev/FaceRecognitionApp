<p align="center">
    <img alt="Face Recognition Brain" src="https://github.com/RayBDev/FaceRecognitionApp/blob/master/src/components/Logo/brain.png" width="60" />
</p>
<h1 align="center">
  Face Recognition Brain
</h1>

The Face Recognition Brain is a single page React application that asks you to log in and enter an image URL. It will then go on to detect the face using the Clarifai API and draw a box around the face it detects. It will also keep track of the amount of faces you've detected in a backend database.

You may use the following credentials if you don't want to register:

```
Email:demo@demo.com
Password: demo
```

## :bookmark_tabs: Technologies Used

1.  **HTML5 & CSS3**

    This responsive layout was created in HTML5 and CSS3. It uses the tachyons CSS toolkit for design as it was quick and easy to set up to create the desired layout.

2.  **REACT**

    React was used heavily throughout this project with multiple components. This was to create functional, maintainable, and scalable code.

3.  **NodeJS + PostgreSQL**

    NodeJS was used for the signin, register and user info endpoints. PostgreSQL allowed for better database segmentation due to its relational nature.

4. **Heroku**

    The application is hosted on Heroku due to its backend requirements.

## :computer: Getting Started

The easiest way to view this project is to follow [this link](https://facerecognition-smartbrain.herokuapp.com/).

You may also clone this repo to view the code and run it directly on your local machine.

*Note: This is only the front-end portion to the application. Please see [FaceRecognitionAPI](https://github.com/RayBDev/FaceRecognitionAPI) for the backend code.*

1.  **Clone the repo**

    Clone the repo to your local computer.

    ```sh
    # cd to your desired directory
    git clone https://github.com/RayBDev/FaceRecognitionApp.git
    ```

3.  **Install Dependencies**

    Navigate to the root project directory

    ```sh
    npm install
    ```

4.  **Start the Server**

    View the project live on your local machine at `http://localhost:3000`

    ```sh
    npm start
    ```

## :email: Contact Me

Contact me and view my portfolio at <https://rbernard.ca>
