### CaliforniaHousePricing

Clone the repository:

```
    git clone <repository_url>
```

Change directory into the cloned repository:
```
    cd <repository_directory>
```

Steps to activate virtual environment
```
    python -m venv myenv
```

To activate...

```
    myenv\Scripts\activate
```

Build the Docker image:

```
    docker build -t my_house_price_predictor .
```

Run the Docker container:

```
    docker run -p 5000:8080 my_house_price_predictor
```

Simply run this code in terminal with correct path i.e. in CaliforniaHousePricing
```
    python wsgi.py
```
