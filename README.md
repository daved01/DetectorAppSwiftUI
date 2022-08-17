# DetectorAppSwiftUI
Code for the two tutorials on how to make an object detection app with a SwiftUI-based interface.
Both tutorials exist as posts and videos.

## Part 1 
PreviewLayer which presents a live camera feed. [Post](https://www.neuralception.com/detection-app-tutorial-camera-feed/) | [video](https://www.youtube.com/watch?v=R2STbo53_vc).
The code is in the tag `previewLayer`.

## Part 2
Adding an object detection model. [Post](https://www.neuralception.com/detection-app-tutorial-detector/) | [video]().
The code is in the tag `detector`.

# Accessing tags
Since the code for the detector in part 2 is based on the one for the previewLayer in part 1, you can access part 1 and 2 with tags.
If you are not familiar with tags here's how to do it.

In Github click on the branches tab and then select `Tags`.

In git, first make sure you have all tags locally after you cloned this repository:

```
git fetch --all
```

Then, use 

```
git checkout previewLayer
```

to see the code for part 1 for example.
