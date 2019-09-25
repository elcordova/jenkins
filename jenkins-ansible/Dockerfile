FROM jenkins/jenkins

USER root
RUN curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py" && python get-pip.py
RUN pip install ansible==2.6.0
USER jenkins
