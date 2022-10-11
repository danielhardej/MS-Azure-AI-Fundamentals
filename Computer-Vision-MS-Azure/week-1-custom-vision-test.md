# Computer Vision in Microsoft Azure
## Classify Images with the Custom Vision Service - Test

#### You are planning on creating an AI solution that will use Computer Vision capabilities.To access the APIs, what two pieces of information do you need to use?

- [x] An endpoint
- [ ] A key
- [x] A connection string

#### You trained a Custom Vision model, you're satisfied with its evaluated performance and you’ve also published the model to your Azure resource. To use the model to make predictions, what information do developers need to use?

- [x] Prediction key
- [x] Model name
- [ ] Recall value
- [x] Project ID
- [x] Prediction endpoint

*To use the model, client application developers need the following information: Project ID, model name, prediction endpoint, and prediction key.*

#### You want to build a solution that needs to detect images that contain adult content or depict violent, gory scenes. Which service would you use to achieve the task?

- [x] Computer Vision
- [ ] Custom Vision
- [ ] A combination of both services

*Computer vision offers the capability to moderate content.*

#### True or False? To use the image classification capability with Custom Vision, you just have to deploy the service and then start generating predictions.

- [ ] True
- [x] False

*Creating an image classification solution with Custom Vision consists of two main tasks. First, you must use existing images to train the model, and then you must publish the model so that client applications can use it to generate predictions.*

#### You plan on creating a solution that will scan a gallery of photos for images that contain product placement. Which capability of Computer Vision should you use?

- [x] Detect brands
- [ ] Categorize an image
- [ ] Detect domain-specific content

*The detect brands capability can help in identifying brands, and works well for product placement.*

#### You want to use the Computer Vision service with images where the dominant foreground color is red. Which of the following capabilities should you use?

- [x] Detect image color schemes
- [ ] Optical character recognition
- [ ] Detect image types

*Detect image color schemes capability can identify the dominant foreground, background, and overall colors in an image.*

#### True or False? To train a classification model, you must upload images to your training resource and label them with the appropriate class labels.

- [x] True
- [ ] False

*To train a classification model, you must upload images to your training resource and label them with the appropriate class labels.*

#### You are training your image classification model and you realize that some images are not classified ly. What should you do to improve the model?

- [x] Add additional images to the training set
- [ ] Add new labels to the model
- [ ] C: Reduce the number of images used for the training set

*The more images in the training set, the better the model will understand patterns and the more accurate its predictions will be.*

#### You are creating a solution that needs to identify if celebrities are present in images and also to determine their age. What capabilities should you take into account?

- [ ] Categorize an image
- [x] Detect domain-specific content
- [x] Detect faces

*You can detect celebrities with the detect domain-specific content feature, while the age can be determined by the detect faces feature.*

#### You are creating a solution that needs to extract handwritten text from several image scans. Which Computer Vision capability should you use?

- [x] Optical character recognition
- [ ] Detect domain-specific content
- [ ] Describe an image

*The Computer Vision service can use optical character recognition (OCR) capabilities to detect printed and handwritten text in images.*
