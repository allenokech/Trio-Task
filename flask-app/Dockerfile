#Use Python Image
FROM python:3.7
# Install apt dependencies
Run apt install update
# Copy contents into image
COPY . .
# run pip dependencies
RUN pip install -r requirements.txt
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT [ "python3", "app.py" ] 