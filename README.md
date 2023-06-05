# Timetable Web Application

This web application allows users to modify and preview timetables based on a provided URL. It also provides the functionality to capture and save a screenshot of the preview.

## Features

- Modify URL: Users can enter a URL, date, and stream to modify the URL and generate a modified URL based on the provided parameters.
- Preview Timetable: The modified URL is used to display a preview of the timetable in an iframe within the web application.
- Open Modified URL: Users can open the modified URL in a new tab to view the timetable separately.
- Capture Screenshot: Users can capture a screenshot of the timetable preview and save it as an image file (JPEG format).

## How to Use

1. Clone the repository or download the source code.

2. Open the `index.html` file in a web browser.

3. On the web page, you will find the following input fields:
   - **Enter URL**: Enter the initial URL of the timetable.
   - **Date**: Select the desired date.
   - **Stream**: Choose the stream from the available options.
   - **Week**: Displays the week number based on the selected date.

4. Modify the URL: Click on the "Modify URL" button to generate the modified URL based on the provided parameters. The modified URL will be displayed in the "Modified URL" input field.

5. Preview Timetable: The generated modified URL will be used to display the timetable preview in the iframe below the input fields.

6. Open Modified URL: Click on the "Open Modified URL in New Tab" button to open the modified URL in a new browser tab. This allows you to view the timetable separately.

7. Capture Screenshot: Click on the "Save Preview as Picture" button to capture a screenshot of the timetable preview and save it as a JPEG image file. The image will be downloaded automatically with the filename "preview.jpg".

## Dependencies

This web application uses the following external library:

- [html2canvas](https://html2canvas.hertzen.com/) - Used for capturing screenshots of the preview section.

## License

[MIT License](LICENSE)

Feel free to modify and customize the code according to your needs.

