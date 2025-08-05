# **Markdown Files Stitcher**

A simple, client-side web application for stitching multiple Markdown (.md) or plain text (.txt) files into a single, cohesive output Markdown file. This tool runs entirely in your browser, ensuring your data remains private and local.

## **✨ Features**

* **File Upload:** Easily upload multiple Markdown or text files.  
* **Drag-and-Drop Reordering:** Intuitive interface to reorder your files before stitching.  
* **Keyboard Reordering:** Accessible reordering using arrow keys for enhanced usability.  
* **Dynamic File Naming:** Output file is automatically named output-markdown-\<datetime\>.md.  
* **Content Headers:** Each stitched file's content is preceded by its original filename as a Markdown heading.  
* **No Backend:** All processing happens locally in your browser, guaranteeing data privacy.  
* **Light & Dark Themes:**  
  * **Automatic Detection:** Detects your OS/browser's preferred color scheme (prefers-color-scheme).  
  * **Manual Toggle:** A convenient switch in the top-right corner allows you to manually switch between light and dark modes.  
  * **Preference Persistence:** Your chosen theme is saved in local storage for future visits.  
* **Responsive Design:** Adapts seamlessly to various screen sizes, from mobile to desktop.  
* **Robust Error Handling:** Provides clear feedback for file reading and stitching issues.

## **🚀 How to Use**

1. **Download/Clone:** Get the index.html file (or the entire repository) to your local machine.  
2. **Open in Browser:** Open the index.html file directly in your web browser (e.g., Chrome, Firefox, Edge).  
3. **Upload Files:**  
   * Click the **"Select Files"** button and choose one or more .md or .txt files from your computer.  
   * Alternatively, **drag and drop** your files directly into the designated upload area.  
4. **Reorder Files:**  
   * **Drag & Drop:** Click and hold a file item in the list, then drag it to your desired position.  
   * **Keyboard Navigation:** Use the Tab key to focus on a file item, then use the Arrow Up or Arrow Down keys to move it within the list.  
5. **Stitch Files:** Click the **"Stitch Files"** button. The application will combine the contents of your files in the order displayed.  
6. **Download Output:** Once stitched, a **"Download Output"** button will appear. Click it to download your combined Markdown file.

## **💡 Theme Switching**

The application automatically detects your system's preferred theme (light or dark). You can manually override this:

* Look for the **sun/moon icon** in the top-right corner of the main content area.  
* Click this icon to toggle between light and dark themes. Your preference will be saved for future visits.

## **♿ Accessibility**

This application is built with **WCAG 2.1 AA compliance** in mind, featuring:

* **Semantic HTML5:** Proper use of HTML elements for better structure and screen reader interpretation.  
* **ARIA Attributes:** role and aria-label attributes are used to enhance accessibility for dynamic content and interactive elements.  
* **Focus Management:** Clear visual focus indicators and proper focus management for keyboard navigation and reordering.  
* **Color Contrast:** Designed with sufficient color contrast for readability in both light and dark themes.  
* **Accessible File Upload:** Utilizes a label for the file input, improving usability for all users.

## **📄 License**

This project is licensed under the **MIT License**.