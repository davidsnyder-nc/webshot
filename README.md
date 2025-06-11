WebShot - Responsive Screenshot Generator
WebShot is a powerful, modern web utility designed to help developers and designers preview and capture screenshots of websites across multiple device viewports. With a sleek dark theme and an intuitive workflow, it's the perfect tool for testing responsive designs and generating high-quality marketing materials.

Features
Live Device Previews: Instantly see how your website looks on phone, tablet, and desktop viewports.

API-Powered Screenshots: Integrates with leading screenshot services (APIFlash, ScreenshotOne) to generate reliable, high-quality images.

Local Development Support: Clear instructions on how to use ngrok to securely create a public URL for your local development server, allowing the API to capture it.

Responsive Testing Tools: Easily rotate mobile and tablet previews between portrait and landscape modes.

Manual Screenshot Helper: A "Pop-out" feature opens the live preview in a new, correctly sized window for easy manual screenshotting.

Modern UI: A clean, dark-themed interface that's easy on the eyes.

Persistent Settings: Remembers your API keys and preferred service in your browser's local storage for convenience.

URL History: Keeps a list of your recently used URLs for quick access.

How to Use
Load a Website:

Enter a public URL (e.g., https://example.com) into the input box and click "Load Preview".

For Local Development: If your site is running on localhost, you must expose it to the internet using ngrok.

Open your terminal and run ./ngrok http YOUR_PORT --host-header="localhost:YOUR_PORT".

Copy the public https://...ngrok-free.app URL provided by ngrok and paste it into the URL input box.

Preview Your Site:

Use the tabs to switch between Phone, Tablet, and Desktop views.

Use the Rotate button to toggle between portrait and landscape modes on the phone and tablet previews.

Use the Pop-out button at any time to open the live preview in a new window, correctly sized for the selected device. This is ideal for taking manual screenshots with your computer's built-in tools.

Generate API Screenshots:

Click the Settings cog icon in the header to open the API settings panel.

Select your preferred screenshot service (APIFlash or ScreenshotOne) from the dropdown.

Enter your API key for the selected service. Your key will be saved in local storage for future use.

Click the "Generate API Image" button for the specific device you want to capture.

The generated screenshot will appear in the preview window. The Download button will become active, allowing you to save the image.

Technologies Used
HTML5 & CSS3: For the core structure and styling.

Tailwind CSS: For rapid, utility-first styling.

JavaScript: To handle all application logic, user interactions, and API calls.

ScreenshotOne / APIFlash: External APIs for generating robust, high-quality screenshots.

ngrok: For securely exposing local web servers to the internet.

This README provides a comprehensive guide for anyone looking to use or contribute to the WebShot project.
