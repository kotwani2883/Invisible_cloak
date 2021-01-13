# Invisible_cloak
It’s the cloak that makes Harry Potter invisible

## Working!!
This technique is opposite to the Green Screening. In green screening, we remove background but here we will remove the foreground frame.
Following steps should be executed->
* Capture and store the background frame (backgound.py)
* Detect the defined color using color detection and segmentation algorithm.
* Segment out the defined colored part by generating a mask.
* Generate the final augmented output to create a magical effect
