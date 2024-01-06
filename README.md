# UPCHAT

This a chatbot powered by RASA intended to answer FAQs about UP (University of the Philippines). Sample FAQs were extracted from https://up.edu.ph/frequently-asked-questions/ <br>
Currently, UPCHAT can answer 3 FAQs:
- How can one qualify for admission into UP?
- What are the degree courses offered by UP?
- What is UP’s tuition rate?

## Set-up
Open command line in the same directory of this project.

1. Install venv
    ```bash
    pip install virtualenv
    ```
2. Create virtual env
    ```bash
    virtualenv my-chatbot
    ```
3. Activate my-chatbot
    ```bash
    my-chatbot\Scripts\activate
    ```
4. Install RASA in virtual env
    ```bash
    pip install rasa
    ```
5. Train UPCHAT
    ```bash
    cd app
    rasa train
    ```
6. To deactivate virtual env,
    ```bash
    deactivate
    ```

## Usage
Open command line in the same directory of this project.
1. Activate my-chatbot
    ```bash
    my-chatbot\Scripts\activate
    ```
2. Go to app directory
    ```bash
    cd app
    ```
3. Run UPCHAT
    ```bash
    rasa shell
    ```
4. Interact with UPCHAT. Enter "/stop" to end chat.
5. To deactivate virtual env,
    ```bash
    deactivate
    ```