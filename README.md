# Shirt_Colour_Detection
The "Shirt_Colour_Detection" project uses YOLO for shirt detection in images/webcam feeds. It extracts dominant colors via KMeans clustering and displays results via Streamlit. Users upload images or use live cameras to identify shirt colors with OpenCV, PIL, and PyTorch integration.

<!DOCTYPE html>
<html>
<head>
    <title>Shirt Colour Detection</title>
</head>
<body>
    <h1>Shirt Colour Detection</h1>
    <p>Detect shirt colors in images/webcam using YOLO and KMeans clustering.</p>
    
    <h2>Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone [your-repo-url]</code></pre>
        <li>Install dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Run the app:</li>
        <pre><code>streamlit run shirt.py</code></pre>
    </ol>

    <h3>Libraries Used</h3>
    <ul>
        <li>Streamlit, Ultralytics YOLO, OpenCV, NumPy, PIL, scikit-learn, PyTorch</li>
    </ul>
</body>
</html>
