# Welcome to the Evaluation!


## Read Before Taking Any Action
## Overview
This session aims to evaluate the outputs of the 'Haptic Repurposing with GenAI' system. You'll be asked to assess each generated result as either 'success' or 'failure' using the provided interface.

## Instructions
- **Navigation**: Each page of the test displays a title, an image, and a video:
  - **Image**: Located on the left, showing the original item.
  - **Title**: Above the content, indicating the generation prompt.
  - **Video**: On the right, displaying the generated result.  
    
- Your task is to judge whether the generated result meets expectations by clicking either the 'success' or 'fail' button.  
- The dataset contains 800 generated results, each with 8 unique prompts, totaling 800 tasks. The evaluation takes about 60 minutes.  
- Your progress is automatically saved in a CSV file after all tasks are completed, but you can also save manually at any time. Please ensure you have enough time to complete the session in one go for accurate results.  
-  <span style="color:red">Please note: The image is provided to give you a reference for the original shape, but the similarity in shape between the original and generated models should not influence your judgment. This aspect is handled by specialized algorithms. Your task is to evaluate the quality of the generated content itself.

## Start Now

### How to Launch the Test Environment
To begin the evaluation, you will need to start a local web server on your computer. This will allow you to access the test page through your web browser. Please follow the steps below:
   ```bash
   python -m http.server  
   ```


## Thank You
Thank you for your participation and valuable contributions to the improvement of our system.

## Additional
Each folder represents an object and contains a generated depth map from orignial model, and five generation results based on specific prompts. The subfolders inside contains a generated 360 video and the OBJ format of the final mesh. 


## Source Data
The objects were randomly picked from the ShapeNet:
- (https://shapenet.org/)
