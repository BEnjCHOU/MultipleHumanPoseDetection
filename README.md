# Light weight MultipleHumanPoseDetection with Realsense D435

This is a light weight multiple person pose estimation, using Realsense D435.

I basically modified the "References 1 : multi-person-pose-estimation-in-opencv-using-openpose" example. Instead of using Caffe Model, I used a Tensorflow MobileNet Model provided by ildoonet/tf-pose-estimation

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Author

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

# References
1. please visit https://www.learnopencv.com/multi-person-pose-estimation-in-opencv-using-openpose/ for multiple-pose detection. This tutorial really help me a lot.
2. please visit https://github.com/opencv/opencv/blob/master/samples/dnn/openpose.py on how to use dnn with OpenCV
3. please visit https://github.com/ildoonet/tf-pose-estimation/tree/master/models/graph/mobilenet_thin for light weight pose model.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
