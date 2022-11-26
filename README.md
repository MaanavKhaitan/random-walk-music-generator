# Creating Music with Random Walks
This program tries to create music using random walks, starting from A and then exploring nearby notes to create a tune.
![image](https://user-images.githubusercontent.com/22297592/204111435-5bca8454-3bde-488b-83f8-08fc2ee0953e.png)

I started by applying a Fourier Transform to deconstruct a sound of a C note on the piano, creating a graph of frequencies like this:
![image](https://user-images.githubusercontent.com/22297592/204111207-5a682c00-5f83-4fd9-9a84-f47dcf5ddb47.png)

I then used this info on the info on the ratios between the dominant frequency and the other frequencies to construct piano-like sounds for every other note in the A Minor scale.

Finally, I used a random walk to generate a tune, and visualized this using Matplotlib :)
