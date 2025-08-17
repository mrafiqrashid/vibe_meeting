# Vibe Meeting - Audio Transcriber

Vibe Meeting is a modern web application that allows you to record audio, transcribe it to text, and generate concise summaries of your conversations. The app features a beautiful, responsive UI built with Tailwind CSS and provides PDF export for your summaries.

## Features

- **Record Audio:** Capture your voice directly in the browser.
- **Transcribe Audio:** Send your recording to an external API for fast, accurate transcription.
- **Edit Transcript:** Review and edit the transcribed text as needed.
- **Summarize Text:** Generate a summary of your transcript using an external summarization API.
- **Download as PDF:** Export your summary as a professionally formatted PDF.
- **Modern UI:** Clean, responsive design with smooth transitions and feedback.

## How It Works

1. **Record:** Click "Start Recording" to capture your audio. Stop when finished.
2. **Transcribe:** Submit your recording. The app sends it to a webhook for transcription.
3. **Edit:** Review and edit the transcript if needed.
4. **Summarize:** Click "Summarize Text" to generate a summary.
5. **Export:** Download your summary as a PDF for easy sharing.

## Technologies Used

- **HTML5 & JavaScript**: Core logic and UI interactions
- **Tailwind CSS**: For modern, responsive styling
- **jsPDF**: For PDF generation
- **External APIs**: For audio transcription and text summarization

## API Endpoints

- **Transcription:** `https://n8n.adamshahrom.com.my/webhook/audio-to-transcribe`
- **Summarization:** `https://n8n.adamshahrom.com.my/webhook/summarize-text`

> **Note:** These endpoints are used for demo purposes. You may need to replace them with your own services for production use.

## Usage

1. Open `frontend.html` in your browser.
2. Allow microphone access when prompted.
3. Follow the on-screen instructions to record, transcribe, and summarize audio.

## Customization

- **API Integration:** Update the `WEBHOOK_URL` and `SUMMARY_URL` constants in the script section to use your own backend services.
- **Styling:** Modify the Tailwind CSS classes or custom styles in the `<style>` block for branding.

## License

This project is provided for educational and demonstration purposes. Please check the API endpoints' terms of use before deploying publicly.

---

**Vibe Meeting** — Transform your conversations into insights.
