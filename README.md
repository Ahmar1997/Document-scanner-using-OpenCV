# Document Scanner
This program allows you to use your webcam to detect documents and provide a warped image scan view of them. It is useful for situations where you need to quickly scan a document without having access to a traditional scanner.

## Installation
1. Clone the repository:  
`git clone https://github.com/Ahmar1997/Document-scanner-using-OpenCV.git`

2. Install the required packages:  
`pip install opencv-python`  
`pip install numpy`

3. Run the program:  
`python document_scanner.py`

## Usage
Launch the program by running the document_scanner.py file.

Position your document in front of your webcam.

It will automatically detect the document in the frame and show it as a warped image

## Result
![result](https://user-images.githubusercontent.com/116836999/225960284-0cb767c5-71a9-4028-b9d9-b346ad9553d2.png)


## How it works
The program uses OpenCV to capture frames from the webcam and apply image processing techniques to detect the document. The detected document is then transformed using a perspective transform to provide a warped scan view.

## Future improvements
Add support for multiple documents on the same page.
Improve the document detection algorithm to handle skewed documents.
Add support for saving the scanned images to a file.


## Contributing
Contributions are always welcome! If you have any suggestions or improvements, please create a pull request or open an issue.
