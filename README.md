# ComicCraft – AI Comic Story Creator

ComicCraft is a web application that transforms a short story idea into a comic. It uses Google Gemini to create a comic outline and panel dialogue, generates panel artwork, provides a browser preview, and exports the finished comic as a PDF.

## Features

- Create a comic from a story prompt
- Choose a genre, tone, and number of panels
- Generate panel-by-panel story text and dialogue with Gemini
- Generate comic-panel artwork
- Preview the complete comic in the browser
- Export comics as PDF files

## Built with

- Python and FastAPI
- HTML, CSS, and Jinja2
- Google Gemini API
- Diffusers, Transformers, and PyTorch
- FPDF2

## Run locally

```powershell
pip install -r requirements.txt
```

Create a `.env` file in the project folder:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Start the application:

```powershell
uvicorn app.main:app --reload
```

Then open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Security

Do not commit your `.env` file or API keys. The supplied `.gitignore` already excludes them.
