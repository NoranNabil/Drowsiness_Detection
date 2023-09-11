# Drowsiness Detection Model
This project is a small implementation of a drowsiness detection deep learning model.
The model determines if a person is becoming drowsy or falling asleep, with the goal of improving driver safety.

## Features

- Real-time drowsiness detection using a webcam or video input.
- The driver status updates is being sended to a message broker on a specific topic,
  these updates are then consumed by the driver's car dashboard and the manager's mobile application for real-time monitoring and display.

## Dependencies

-All dependencies are metioned in the colab notebooks.

## Testing

The testing code for this project is implemented in a Google Colab notebook.
Google Colab provides a convenient platform for running Python code in a cloud-based Jupyter notebook environment.

To execute the testing code, follow these steps:

1. Open Google colab.
2. From file -> open notebook -> GitHub -> Enter "https://github.com/NoranNabil/Drowsiness_Detection/tree/main" -> press Enter
3. Select the Drowsiness_Detection_Deployment.ipynb for testing.
4. Using your kaggle.json, you can get the model wieghts for testing.
5. Test using the lab top camera or on your own viedo.
6. Get your message and you can send it over the broker and the specified topic to a dashboard for taking action.

Please note that Google Colab requires a Google account to access and use the notebook. If you don't have a Google account, you can create one for free at "https://accounts.google.com/signup".

## Customization and Extension
The project can be customized and extended in various ways, such as:
-Integrating the model with other driver safety systems or frameworks.

Feel free to explore the code and experiment with different configurations to suit your needs.

## Contributing
Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
