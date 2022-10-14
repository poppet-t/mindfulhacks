from python:3.9

workdir /code

# copying stuff from local directory into container
copy ./datasets /code/datasets
copy ./SMS-Message-Spam-Detector /code/SMS-Message-Spam-Detector


copy ./requirements.txt /code
run ls
run pip install -r requirements.txt

expose 5000

CMD python SMS-Message-Spam-Detector/app.py







