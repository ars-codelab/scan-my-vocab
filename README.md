Scan My Vocab Builder
======================================

A simple, powerful web application to scan vocabulary from physical textbooks using your phone's camera and create interactive flashcard decks for studying.

The Problem
-----------

Learning a new language like Japanese often involves working with physical textbooks. While these books are a great source of knowledge, they present a major challenge for revision. It's difficult to quickly test your memory of the vocabulary you've just learned without manually creating flashcards, which is a slow and tedious process. This app was built to solve that exact problem.

The Solution
------------

**Scan My Vocab Builder** bridges the gap between your physical textbook and modern digital study methods. It allows you to:

*   **Scan Pages:** Use your phone's camera or upload an image of a textbook page. The app uses Google's powerful AI to automatically perform Optical Character Recognition (OCR) and extract the vocabulary.
    
*   **Review and Correct:** Instantly review the scanned words. You can correct any OCR errors, delete words you don't need, or even manually add words the scanner might have missed.
    
*   **Organize Your Decks:** Save your vocabulary into custom "Books" and "Chapters," mirroring the structure of your textbook.
    
*   **Edit Anytime:** Easily manage your decks. You can rename chapters and add, edit, or delete words within any chapter at any time.
    
*   **Quiz Yourself:** Test your knowledge with an interactive flashcard quiz mode for any chapter or an entire book.
    
*   **Portable Decks:** Export your entire vocabulary collection to a JSON file for backup, and import it back into the app on any device.
    

How to Run This App
-------------------

This is a self-contained client-side application. It consists of a single index.html file with all the necessary HTML, CSS, and JavaScript.

The easiest way to host it for free is using **GitHub Pages**:

1.  Create a new public repository on GitHub (e.g., japanese-vocab-builder).
    
2.  Upload the index.html file from this project to the repository.

3.  This App was built primary for Japanese to English Learning, but it can be changed easily to any language by editing the LLM prompt in the code 
    
4.  Go to your repository's **Settings** tab.
    
5.  In the left sidebar, click on **Pages**.
    
6.  Under "Branch," select your main branch (usually main or master) and click **Save**.
    
7.  GitHub will provide you with a public URL where your app is now live (e.g., [https://your-username.github.io/japanese-vocab-builder/](https://ars-codelab.github.io/scan-my-vocab/)).

8. You could further shorten this URL using an URL shortener service like bit.ly (e.g. [https://bit.ly/scan-vocab](bit.ly/scan-vocab))  
    

Usage Guide
-----------

1.  **Get an API Key:** This app requires a Google AI API key to function.
    
    *   Go to [Google AI Studio](https://aistudio.google.com/app/apikey) to generate your free key.
        
    *   Open the Japanese Vocab Builder app and click the **gear icon (⚙️)** in the top-right corner.
        
    *   Enter your API key and click "Save Key." The key will be saved securely in your browser's local storage for future use.
        
2.  **Add Words:**
    
    *   On the home screen, click **Add New Words**.
        
    *   Click **Use Camera** to open your phone's camera and take a picture of a page, or click **Upload File** to select an image from your device.
        
    *   Once you've added all the pages you want to scan, click **Extract Vocabulary**.
        
3.  **Review and Organize:**
    
    *   The app will display the words it found. Correct any mistakes directly in the text fields.
        
    *   Uncheck any words you don't want to add.
        
    *   Click **Add Selected Words to a Deck**.
        
    *   In the pop-up, choose an existing Book and Chapter, or create new ones, then click **Save to Deck**.
        
4.  **Study:**
    
    *   From the home screen, find the book and chapter you want to study.
        
    *   Click **Quiz** to start the flashcard session.
        
    *   Click **Edit** to manage the words or rename the chapter.
        

Technology Stack
----------------

*   **HTML5**
    
*   **Tailwind CSS** for styling.
    
*   **Vanilla JavaScript** for all application logic.
    
*   **Google AI (Gemini)** for the OCR and vocabulary extraction.


Filing Issues / Bugs
-------------------
If you find any bugs with the app, please provide relevant details via an [Issue](https://github.com/ars-codelab/scan-my-vocab/issues). I will usually respond within 2-3 days. Thanks!
