Forensic Speaker Recognition

This project implements an automated forensic speaker recognition system that analyzes and compares two audio samples to determine if they belong to the same speaker.

🚀 Features
Audio Preprocessing: Noise reduction and bandpass filtering for better speech clarity.
Speech-to-Text Transcription: Uses AssemblyAI for accurate speech recognition.
Language Detection: Automatically identifies and processes English and Hindi speech.
Stopword Removal: Filters out common stopwords to focus on relevant speech features.
Feature Extraction: Computes MFCC, spectral centroid, spectral bandwidth, RMS energy, zero crossing rate, and pitch.
Speaker Similarity Analysis: Compares extracted audio features and calculates differences.
PDF Report Generation: Generates a detailed forensic analysis report.
Gradio UI: Provides an easy-to-use web interface for uploading and analyzing audio files.

🛠️ Technologies Used
1. Python
2. Librosa (Audio Processing)
3. AssemblyAI (Speech-to-Text)
4. NLTK (Stopword Removal)
5. Gradio (Web Interface)
6. FPDF (PDF Report Generation)

📄 Output
Analysis Report (Text & PDF)
Speaker Similarity Conclusion

💡 Ideal for forensic analysis, speaker verification, and voice authentication tasks.
