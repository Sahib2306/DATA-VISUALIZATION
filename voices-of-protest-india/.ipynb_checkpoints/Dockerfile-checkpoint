# Use a stable, well-supported Python image
FROM python:3.10-slim

# Set working directory inside the container
WORKDIR /app

# Copy dependency file first (for caching)
COPY requirements.txt ./

# Install dependencies + Jupyter
RUN pip install --no-cache-dir -r requirements.txt jupyter

# Copy all project files into the container
COPY . .

# Expose Jupyter Notebook default port
EXPOSE 8888

# Default command: run Jupyter Notebook server
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--allow-root", "--no-browser"]
