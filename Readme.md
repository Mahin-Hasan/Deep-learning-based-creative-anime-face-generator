## Deep learning based creative anime face generator to support artists and anime illustrators

### How to Run the notebook
1. Download the anime face dataset (63,632 images).
2. Place all images in a folder named `images`.
3. Run the notebook to train and save the generator model.
4. Launch the FastAPI server to generate faces via API.

### Requirements
- Python 3.8+
- PyTorch
- FastAPI
- torchvision

### API Endpoints
- `GET /` — Checks if the server running
- `GET /generateAnime"` — Generates single anime face each time the GET request is sent.
