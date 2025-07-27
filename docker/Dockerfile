FROM python:3

WORKDIR /usr/src/app

# Copy the source code into the container
COPY . .

# Create a Python virtual environment
RUN python -m venv venv

# Activate the virtual environment and install the package
RUN . venv/bin/activate && pip install --no-cache-dir .

# Set the virtual environment as the default Python environment
ENV PATH="/usr/src/app/venv/bin:$PATH"



