<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Learning</title>
</head>

<body>

    <h1>Daily Learning</h1>

    <img 
    alt="Cloudy morning"
    src="https://octodex.github.com/images/cloud.jpg"
    width="100"
    align="right">

    <h2>Morning Planning</h2>

    <ul>
        <li>
            Check out the 
            <a href="https://github.blog/">
                github blog
            </a>
            for topic ideas.
        </li>

        <li>
            Learn about 
            <a href="https://skills.github.com/#first-day-on-github">
                GitHub Pages
            </a>.
        </li>

        <li>
            Convert my first blog post into an actual webpage.
        </li>
    </ul>

    <h2>Review</h2>

    <p>
        Convert an image or video from dark mode to light mode using 
        <a href="https://www.ffmpeg.org">
            ffmpeg
        </a>
    </p>

    <pre>
<code>
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
</code>
    </pre>

</body>
</html>
