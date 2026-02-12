git clone https://github.com/Nabil780554/sirius-test.git
cd sirius-test
docker build -t sirius-test .
docker run -d -p 8501:8501 sirius-test
