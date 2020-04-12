# Portal for Airavata Managed File Transfer

Airavata Managed File Transfer is a standalone service to orchestrate data movement between various cloud and high performance computing storages. The MFT Portal provides a dashboard to monitor and users to request the transfers. 

### Getting Started

1.  Checkout this project and create a virtual environment.

    ```
    cd airavata-mft-portal
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
2. Build js files
    ```
    ./build_js.sh
    ```
2.  Run the server

    ```
    python manage.py runserver
    ```

3. Point your browser to http://localhost:8000/workspace/storage/

